<script>
    import {products, cart} from './card.js'

const addToCart = (product) => {
    for(let item of $cart) {
            if(item.id === product.id) {
                product.quantity += 1
                $cart = $cart;
                return;
            }
    }
    $cart = [...$cart, product]
}
</script>

<div class="container-fluid py-5">
	<div class="mx-auto text-center mb-5" style="max-width: 500px;">
        <h6 class="text-primary text-uppercase">Các sản phẩm</h6>
        <h1 class="display-5">Trái cây</h1>
    </div>
    
    <div class="container">
        {#each $products as product}
        <div class="product-card">
            <div class="badge">Hot</div>
            <div class="product-tumb">
                <img src={product.image} alt="">
            </div>
            <div class="product-details">
                <span class="product-category">{product.name}</span>
                <h4>{product.name}</h4>
                <p>{product.content}</p>
                <div class="product-bottom-details">
                    <div class="product-price text-secondary"><small style="color: red;">{product.prices.toString()} đ</small>{product.price.toString()} đ</div>
                    <div class="product-links">
                        <button ><i class="fa fa-heart"></i></button>
                        <button on:click={() => addToCart(product)}><i class="fa fa-shopping-cart"></i></button>
                    </div>
                </div>
            </div>
        </div>
        {/each}
    </div>
</div>


<style>
.container{
    position: relative;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    padding: 30px;
}
button
{
    text-decoration: none;
}
.container .product-card {
    width: 20%;
    position: relative;
    box-shadow: 0 2px 7px #aaa9a9;
    margin: 20px 10px;
    background: #fafafa;
    display: flex;
    flex-direction: column;
    transition: 0.3s ease-in-out;
    
    
}

.badge {
    position: absolute;
    left: 0;
    top: 20px;
    text-transform: uppercase;
    font-size: 13px;
    font-weight: 700;
    background: red;
    color: #fff;
    padding: 3px 10px;
}

.product-tumb {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 300px;
    padding: 50px;
    background: #ffffff;
}

.product-tumb img {
    max-width: 100%;
    max-height: 100%;
}

.product-tumb:hover img{
    transform: scale(1.1);
}

.product-details {
    padding: 15px;
    background: #f0f0f0;
    box-shadow: 0 2px 7px #aaa9a9;

}

.product-category {
    display: block;
    font-size: 12px;
    font-weight: 700;
    text-transform: uppercase;
    color: #ccc;
    margin-bottom: 18px;
}

.product-details h4 button {
    font-weight: 500;
    display: block;
    margin-bottom: 18px;
    text-transform: uppercase;
    color: #363636;
    text-decoration: none;
    transition: 0.3s;
}

.product-details h4 button:hover {
    color: #fbb72c;
}

.product-details p {
    font-size: 15px;
    line-height: 22px;
    margin-bottom: 10px;
    color: #999;
}

.product-bottom-details {
    overflow: hidden;
    border-top: 1px solid #eee;
    padding-top: 10px;
}

.product-bottom-details div {
    float: left;
    width: 50%;
}

.product-price {
    font-size: 18px;
    color: #fbb72c;
    font-weight: 600;
}

.product-price small {
    font-size: 80%;
    font-weight: 400;
    text-decoration: line-through;
    display: inline-block;
    margin-right: 5px;
}

.product-links {
    text-align: right;
}

.product-links button {
    display: inline-block;
    margin-left: 5px;
    color: gray;
    transition: 0.3s;
    font-size: 17px;
    border: 1px solid;
}

.product-links button:hover {
    color: #fbb72c;
}
</style>




        
<!-- <div class="product-list">
    {#each $products as product}
    <div class="imagebg">
        <div class="image" style="background-image: url({product.image})"></div>
    <h4>{product.name}</h4>
    <p>{product.price} VND</p>
    <button on:click={() => addToCart(product)}>Thêm giỏ hàng</button>
    </div>
    {/each}
    </div> -->
    
    <!-- <style>
    .product-list {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
    }
    .imagebg{
        border: 1px solid grey;
        display: block;
        justify-content: center;
        align-items: center;
        margin: 10px;
        border-radius: 10pxs;
    }
    
    .image {
        height: 150px;
        width: 150px;
        margin: 0 auto;
        display: flex;
        justify-content: center;
        background-size: contain;
        background-position: center;
        background-repeat: no-repeat;
        /* border: 1px solid gray; */
    }
    button{
        background-color: black;
        color: whitesmoke;
        border-radius: 10px;
        margin: 10px auto;
        justify-content: center;
        align-items: center;
        display: flex;
        font-size: 20px;
        /* margin-top: 10px; */
    }
    button:hover{
        background-color: green;
        color: whitesmoke;
    }
    h4,p{
        align-items: center;
        width: 100%;
        margin: 0 auto;
        justify-content: center;
        display: flex;
        margin-top: 8px;
    }
    </style>


        -->