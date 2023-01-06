<script>
    import coe1 from '../img/coe1.png'
	import coe2 from '../img/coe2.png'
	import coe3 from '../img/coe3.png'
	import coe4 from '../img/coe6.png'
	import coe5 from '../img/coe5.png'
</script>



<svelte:head>
	<title>Sản phẩm</title>
	<meta name="description" content="About this app" />
</svelte:head>



<!-- Products Start -->
<div class="container-fluid py-5">
	<div class="container">
		<div class="mx-auto text-center mb-5" style="max-width: 500px;">
			<h6 class="text-primary text-uppercase">Các sản phẩm</h6>
			<h1 class="display-5">Coffee đóng hộp</h1>
		</div>
		<div class="owl-carousel product-carousel px-5 d-flex">
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe1} alt="">
					<h6 class="mb-3">Cà Phê Rang Xay Original 1 Túi 1KG</h6>
					<h5 class="text-primary mb-0">235.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe2} alt="">
					<h6 class="mb-3">Cà Phê Hòa Tan Đậm Vị Việt Túi 40x16G</h6>
					<h5 class="text-primary mb-0">99.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe3} alt="">
					<h6 class="mb-3">Cà Phê Rang Xay Original 1 250g</h6>
					<h5 class="text-primary mb-0">60.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe4} alt="">
					<h6 class="mb-3">Cà Phê Hoà Tan Đậm Vị Việt (18 gói x 16 gam)</h6>
					<h5 class="text-primary mb-0">48.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe5} alt="">
					<h6 class="mb-3">Cà Phê Sữa Đá Hòa Tan Túi 25x22G</h6>
					<h5 class="text-primary mb-0">99.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
		</div>
        <!-- 2 -->
        <div class="owl-carousel product-carousel px-5 d-flex">
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe1} alt="">
					<h6 class="mb-3">Cà Phê Rang Xay Original 1 Túi 1KG</h6>
					<h5 class="text-primary mb-0">235.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe2} alt="">
					<h6 class="mb-3">Cà Phê Hòa Tan Đậm Vị Việt Túi 40x16G</h6>
					<h5 class="text-primary mb-0">99.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe3} alt="">
					<h6 class="mb-3">Cà Phê Rang Xay Original 1 250g</h6>
					<h5 class="text-primary mb-0">60.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe4} alt="">
					<h6 class="mb-3">Cà Phê Hoà Tan Đậm Vị Việt (18 gói x 16 gam)</h6>
					<h5 class="text-primary mb-0">48.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe5} alt="">
					<h6 class="mb-3">Cà Phê Sữa Đá Hòa Tan Túi 25x22G</h6>
					<h5 class="text-primary mb-0">99.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
		</div>
        <!-- 3 -->
        <div class="owl-carousel product-carousel px-5 d-flex">
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe1} alt="">
					<h6 class="mb-3">Cà Phê Rang Xay Original 1 Túi 1KG</h6>
					<h5 class="text-primary mb-0">235.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe2} alt="">
					<h6 class="mb-3">Cà Phê Hòa Tan Đậm Vị Việt Túi 40x16G</h6>
					<h5 class="text-primary mb-0">99.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe3} alt="">
					<h6 class="mb-3">Cà Phê Rang Xay Original 1 250g</h6>
					<h5 class="text-primary mb-0">60.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe4} alt="">
					<h6 class="mb-3">Cà Phê Hoà Tan Đậm Vị Việt (18 gói x 16 gam)</h6>
					<h5 class="text-primary mb-0">48.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe5} alt="">
					<h6 class="mb-3">Cà Phê Sữa Đá Hòa Tan Túi 25x22G</h6>
					<h5 class="text-primary mb-0">99.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
		</div>
        <!-- 4 -->
        <div class="owl-carousel product-carousel px-5 d-flex">
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe1} alt="">
					<h6 class="mb-3">Cà Phê Rang Xay Original 1 Túi 1KG</h6>
					<h5 class="text-primary mb-0">235.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe2} alt="">
					<h6 class="mb-3">Cà Phê Hòa Tan Đậm Vị Việt Túi 40x16G</h6>
					<h5 class="text-primary mb-0">99.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe3} alt="">
					<h6 class="mb-3">Cà Phê Rang Xay Original 1 250g</h6>
					<h5 class="text-primary mb-0">60.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe4} alt="">
					<h6 class="mb-3">Cà Phê Hoà Tan Đậm Vị Việt (18 gói x 16 gam)</h6>
					<h5 class="text-primary mb-0">48.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe5} alt="">
					<h6 class="mb-3">Cà Phê Sữa Đá Hòa Tan Túi 25x22G</h6>
					<h5 class="text-primary mb-0">99.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
		</div>
        <!-- 5 -->
        <div class="owl-carousel product-carousel px-5 d-flex">
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe1} alt="">
					<h6 class="mb-3">Cà Phê Rang Xay Original 1 Túi 1KG</h6>
					<h5 class="text-primary mb-0">235.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe2} alt="">
					<h6 class="mb-3">Cà Phê Hòa Tan Đậm Vị Việt Túi 40x16G</h6>
					<h5 class="text-primary mb-0">99.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe3} alt="">
					<h6 class="mb-3">Cà Phê Rang Xay Original 1 250g</h6>
					<h5 class="text-primary mb-0">60.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe4} alt="">
					<h6 class="mb-3">Cà Phê Hoà Tan Đậm Vị Việt (18 gói x 16 gam)</h6>
					<h5 class="text-primary mb-0">48.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
			<div class="pb-5">
				<div class="product-item position-relative bg-white d-flex flex-column text-center">
					<img class="img-fluid mb-4" src={coe5} alt="">
					<h6 class="mb-3">Cà Phê Sữa Đá Hòa Tan Túi 25x22G</h6>
					<h5 class="text-primary mb-0">99.000 đ</h5>
					<div class="btn-action d-flex justify-content-center">
						<a class="btn bg-primary py-2 px-3" href="/"><i class="bi bi-cart text-white"></i></a>
						<a class="btn bg-secondary py-2 px-3" href="/"><i class="bi bi-eye text-white"></i></a>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
<!-- Products End -->
