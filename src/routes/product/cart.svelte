<script>
	import { cart, products } from './card.js'
    
	// giảm 1 sản phẩm (-)
	const minusItem = (product) => {
		for(let item of $cart) {
				if(item.id === product.id) {
					if(product.quantity > 1 ) {
							product.quantity -= 1
							$cart = $cart
					} else {
							$cart = $cart.filter((cartItem) => cartItem != product)
					}
					return;
				}
		}
	}
	// tăng 1 sản phẩm (+)
	const plusItem = (product) => {
			for(let item of $cart) {
							if(item.id === product.id) {
								product.quantity += 1
								$cart = $cart;
								return;
							}
					}
	}
		// tổng sản phẩm trong giỏ hàng
		$: total = $cart.reduce((sum, item) => sum + item.price * item.quantity + 36, 0)
		// xóa 1 sản phẩm trong giỏ hàng
		const deleteProduct = (product) => {
			$cart =  $cart.filter((proc) => proc.id != product.id)
		}
</script>

<!-- start shopping cart -->

<!-- <h1>Shopping Cart</h1> -->

<div class="shopping-cart">

  <div class="column-labels">
	<label class="product-image" for="">Hình ảnh</label>
	<label class="product-details" for="">Sản phẩm</label>
	<label class="product-price" for="">Tiền</label>
	<label class="product-quantity" for="">Số lượng</label>
	<label class="product-removal" for="">Xóa</label>
	<label class="product-line-price" for="">Tổng tiền</label>
  </div>
  {#each $cart as product }
  {#if product.quantity > 0}
  <div class="product">
    <div class="product-image">
		<img src={product.image} alt="Hình ảnh">
    </div>
    <div class="product-details">
      <div class="product-title">{product.name}</div>
      <p class="product-description">{product.content}</p>
    </div>
    <div class="product-price">{product.price} đ</div>
    <div class="product-quantity">
		<button class="left" on:click={() => plusItem(product)}>+</button>
		&ensp;&ensp;&ensp;&ensp;{product.quantity}&ensp;&ensp;&ensp;&ensp;
		<button class="right" on:click={() => minusItem(product)}>-</button>
    </div>
    <div class="product-removal">
      <button class="remove-product" on:click={() => deleteProduct(product)}>
        Xóa
      </button>
    </div>
    <div class="product-line-price">{product.price * product.quantity} đ</div>
  </div>
  
  {/if}
  {/each}
  <div class="totals">
    <!-- <div class="totals-item">
		<label for="">Tiền: </label>
      <div class="totals-value" id="cart-subtotal">{sums} đ</div>
    </div> -->
    <div class="totals-item">
		<label for="">Thuế vat (5%): </label>
      <div class="totals-value" id="cart-tax">36.000 đ</div>
    </div>
    <div class="totals-item">
		<label for="">Số lượng sản phẩm: </label>
      <div class="totals-value" id="cart-shipping">{$cart.length}</div>
    </div>
    <div class="totals-item totals-item-total">
		<label for="">Tổng tiền: </label>
      <div class="totals-value" id="cart-total">{total} đ</div>
    </div>
  </div>
      <button class="checkout">Thanh toán</button>

</div>

<!-- shopping cart end -->

<!-- <div class="cart-list">
		<div class="cart-item">
			<p class="shop-cart" style="width: 30%; margin:0 auto;font-weight: 600;">Sản phẩm</p>
			<div class="shop-cart">số lượng</div>
			<p class="shop-cart">Số tiền</p>
		</div>
		
	{#each $cart as product }
		{#if product.quantity > 0}
		<div class="cart-item">
			<img width="50" src={product.image} alt={product.name}/>
			<div class="shop-cart">
				<div class="shop-item">
					<button class="left" on:click={() => plusItem(product)}>+</button>
					&ensp;&ensp;&ensp;&ensp;{product.quantity}&ensp;&ensp;&ensp;&ensp;
					<button class="right" on:click={() => minusItem(product)}>-</button>
				</div>
			</div>
			<p class="shop-cart">{product.price.toString() * product.quantity} VND</p>
		</div>
		{/if}
	{/each}
	<div class="total">
		<h4>Tổng thanh toán ({$cart.length} sản phẩm): {total} đ</h4>
		
	</div>
	<button style="float: right; margin: 10px;">Mua hàng</button>
</div> -->


<style>
	/* .cart-item {
		display: grid;
		grid-template-columns: repeat(3, 1fr);
		/* border: 1px solid; *
		border-bottom: 1px solid gray;
		margin: 5px;
		padding: 5px;
	}

	img{
		
		width: 30%;
		margin: 0 auto;
	}


	.shop-cart{
		display: flex;
		justify-content: center;
		align-items: center;
		margin: 15px;
		font-weight: 600;
	}

	button.left{
		margin-right: 15px;
		width: 3em;
		background-color: white;
		color: gray;
		border: 1px solid gray;
	}
	button.right{
		margin-left: 15px;
		width: 3em;
		background-color: white;
		color: gray;
		border: 1px solid gray;
	}

	.total {
		text-align: right;
		margin-top: 25px;
	}
	
	.cart-list {
		border: 2px solid;
		padding: 10px;
		
	} */

	.product-image {
    float: left;
    width: 20%;
}
.product-details {
    float: left;
    width: 37%;
}
.product-price {
    float: left;
    width: 12%;
}
.product-quantity {
    float: left;
    width: 10%;
}
.product-removal {
    float: left;
    width: 9%;
}
.product-line-price {
    float: left;
    width: 12%;
    text-align: right;
}
.group:before, .shopping-cart:before, .column-labels:before, .product:before, .totals-item:before, .group:after, .shopping-cart:after, .column-labels:after, .product:after, .totals-item:after {
    content: '';
    display: table;
}
.group:after, .shopping-cart:after, .column-labels:after, .product:after, .totals-item:after {
    clear: both;
}
.group, .shopping-cart, .column-labels, .product, .totals-item {
    zoom: 1;
}
.product .product-price:before, .product .product-line-price:before, .totals-value:before {
    content: '';
}
body {
    padding: 0px 30px 30px 20px;
    font-family: "HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-weight: 100;
}
h1 {
    font-weight: 100;
}
label {
    color: #aaa;
}
.shopping-cart {
    margin-top: -45px;
}
.column-labels label {
    padding-bottom: 15px;
    margin-bottom: 15px;
	margin-top: 100px;
    border-bottom: 1px solid #eee;
}
.column-labels .product-image, .column-labels .product-details, .column-labels .product-removal {
    text-indent: -9999px;
}
.product {
    margin-bottom: 20px;
    padding-bottom: 10px;
    border-bottom: 1px solid #eee;
}
.product .product-image {
    text-align: center;
}
.product .product-image img {
    width: 100px;
}
.product .product-details .product-title {
    margin-right: 20px;
    font-family: "HelveticaNeue-Medium", "Helvetica Neue Medium";
}
.product .product-details .product-description {
    margin: 5px 20px 5px 0;
    line-height: 1.4em;
}
.product .product-quantity input {
    width: 40px;
}
.product .remove-product {
    border: 0;
    padding: 4px 8px;
    background-color: #c66;
    color: #fff;
    font-family: "HelveticaNeue-Medium", "Helvetica Neue Medium";
    font-size: 12px;
    border-radius: 3px;
}
.product .remove-product:hover {
    background-color: #a44;
}
.totals .totals-item {
    float: right;
    clear: both;
    width: 100%;
    margin-bottom: 10px;
}
.totals .totals-item label {
    float: left;
    clear: both;
    width: 79%;
    text-align: right;
}
.totals .totals-item .totals-value {
    float: right;
    width: 21%;
    text-align: right;
}
.totals .totals-item-total {
    font-family: "HelveticaNeue-Medium", "Helvetica Neue Medium";
}
.checkout {
    float: right;
    border: 0;
    margin-top: 20px;
    padding: 6px 25px;
    background-color: #6b6;
    color: #fff;
    font-size: 25px;
    border-radius: 3px;
}
.checkout:hover {
    background-color: #494;
}
@media screen and (max-width: 650px) {
    .shopping-cart {
        margin: 0;
        padding-top: 20px;
        border-top: 1px solid #eee;
    }
    .column-labels {
        display: none;
    }
    .product-image {
        float: right;
        width: auto;
    }
    .product-image img {
        margin: 0 0 10px 10px;
    }
    .product-details {
        float: none;
        margin-bottom: 10px;
        width: auto;
    }
    .product-price {
        clear: both;
        width: 70px;
    }
    .product-quantity {
        width: 100px;
    }
    .product-quantity input {
        margin-left: 20px;
    }
    .product-quantity:before {
        content: 'x';
    }
    .product-removal {
        width: auto;
    }
    .product-line-price {
        float: right;
        width: 70px;
    }
}
@media screen and (max-width: 350px) {
    .product-removal {
        float: right;
    }
    .product-line-price {
        float: right;
        clear: left;
        width: auto;
        margin-top: 10px;
    }
    .product .product-line-price:before {
        content: 'Item Total: $';
    }
    .totals .totals-item label {
        width: 60%;
    }
    .totals .totals-item .totals-value {
        width: 40%;
    }
}
</style>