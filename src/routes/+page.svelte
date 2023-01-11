<script>
	import coffee1 from './img/coffee-1.png'
	import master1 from './img/master2.png'
	import coe1 from './img/coe1.png'
	import coe2 from './img/coe2.png'
	import coe3 from './img/coe3.png'
	import coe4 from './img/coe6.png'
	import coe5 from './img/coe5.png'
	import nv1 from './img/nv1.png'
	import phong from './img/phong.png'
	import tinh from './img/tinh.png'
	import thien from './img/thien.png'
	

	
</script>

<svelte:head>
	<title>Trang chủ</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>


<!-- Banner Start -->
<div class="container-fluid banner mb-5">
	<div class="container">
		<div class="row gx-0">
			<div class="col-md-6">
				<div class="bg-primary bg-vegetable d-flex flex-column justify-content-center p-5" style="height: 300px;">
					<h3 class="text-white mb-3">MaxWell House:</h3>
					<p class="text-white">DGood to the last drop – Thơm ngon đến giọt cuối cùng</p>
					<a class="text-white fw-bold" href="/">Chi tiết<i class="bi bi-arrow-right ms-2"></i></a>
				</div>
			</div>
			<div class="col-md-6">
				<div class="bg-secondary bg-fruit d-flex flex-column justify-content-center p-5" style="height: 300px;">
					<h3 class="text-white mb-3">Trung Nguyên Legend:</h3>
					<p class="text-white">Cà phê năng lượng – Cà phê đổi đời</p>
					<a class="text-white fw-bold" href="/">Chi tiết<i class="bi bi-arrow-right ms-2"></i></a>
				</div>
			</div>
		</div>
	</div>
</div>
<!-- Banner Start -->

<!-- About Start -->
<div class="container-fluid about pt-5">
	<div class="container">
		<div class="row gx-5">
			<div class="col-lg-6 mb-5 mb-lg-0">
				<div class="d-flex h-100 border border-5 border-primary border-bottom-0">
					<img class="img-fluid mt-auto mx-auto" src={coffee1} alt="">
				</div>
			</div>
			<div class="col-lg-6 pb-5">
				<div class="mb-3 pb-2">
					<h6 class="text-primary text-uppercase">Giới thiệu coffee</h6>
					<h1 class="display-5">Chúng tôi sản xuất ra những cafe thơm ngon cho bạn</h1>
				</div>
				<p class="mb-4">Cà phê là loại cây thân gỗ, độ cao trung bình từ khoảng 2m đến 4m với nhiều đốt và cành thon dài đẹp mắt. Là cà phê có hình Oval, màu xanh thẫm, tương đối rộng với từ 4 đến 6cm. Hoa của loại cây này lại có màu trắng tinh khôi, thuần khiết với 5 cánh trên mỗi hoa và nở thành chùm vô cùng ấn tượng. Hoa có hương thơm dịu nhẹ, thoang thoảng tựa như hương hoa nhài.</p>
				<div class="row gx-5 gy-4">
					<div class="col-sm-6">
						<i class="fa fa-seedling display-1 text-secondary"></i>
						<h4>100% Trái cà phê</h4>
						<p class="mb-0">Cùng Arabica, Robusta cũng là loại cà phê nổi tiếng được sử dụng phổ biến ở Việt Nam và nhiều nước khác trên thế giới. Với nhiều đặc điểm riêng, không...</p>
						
					</div>
					<div class="col-sm-6">
						<i class="fa fa-award display-1 text-secondary"></i>
						<h4>Chứng nhận chất lượng</h4>
						<p class="mb-0">Tại Ritachi Coffee chúng tôi luôn chú trọng đến quản trị tính đồng nhất, ổn định và chất lượng của mỗi sản phẩm mà chúng tôi gửi đến cho khách hàng.</p>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
<!-- About End -->


<!-- Facts Start -->
<div class="container-fluid bg-primary facts py-5 mb-5">
	<div class="container py-5">
		<div class="row gx-5 gy-4">
			<div class="col-lg-3 col-md-6">
				<div class="d-flex">
					<div class="bg-secondary rounded-circle d-flex align-items-center justify-content-center mb-3" style="width: 60px; height: 60px;">
						<i class="fa fa-star fs-4 text-white"></i>
					</div>
					<div class="ps-4">
						<h5 class="text-white">Kinh nghiệm</h5>
						<h1 class="display-5 text-white mb-0" data-toggle="counter-up">25 năm</h1>
					</div>
				</div>
			</div>
			<div class="col-lg-3 col-md-6">
				<div class="d-flex">
					<div class="bg-secondary rounded-circle d-flex align-items-center justify-content-center mb-3" style="width: 60px; height: 60px;">
						<i class="fa fa-users fs-4 text-white"></i>
					</div>
					<div class="ps-4">
						<h5 class="text-white">Chuyên gia</h5>
						<h1 class="display-5 text-white mb-0" data-toggle="counter-up">12566</h1>
					</div>
				</div>
			</div>
			<div class="col-lg-3 col-md-6">
				<div class="d-flex">
					<div class="bg-secondary rounded-circle d-flex align-items-center justify-content-center mb-3" style="width: 60px; height: 60px;">
						<i class="fa fa-check fs-4 text-white"></i>
					</div>
					<div class="ps-4">
						<h5 class="text-white">Dự án</h5>
						<h1 class="display-5 text-white mb-0" data-toggle="counter-up">3665</h1>
					</div>
				</div>
			</div>
			<div class="col-lg-3 col-md-6">
				<div class="d-flex">
					<div class="bg-secondary rounded-circle d-flex align-items-center justify-content-center mb-3" style="width: 60px; height: 60px;">
						<i class="fa fa-mug-hot fs-4 text-white"></i>
					</div>
					<div class="ps-4">
						<h5 class="text-white">Khách hàng</h5>
						<h1 class="display-5 text-white mb-0" data-toggle="counter-up">267450</h1>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
<!-- Facts End -->


<!-- Services Start -->
<div class="container-fluid py-5">
	<div class="container">
		<div class="row g-5">
			<div class="col-lg-4 col-md-6">
				<div class="mb-3">
					<h6 class="text-primary text-uppercase">Dịch vụ</h6>
					<h1 class="display-5">Coffee Dev</h1>
				</div>
				<p class="mb-4">Thời gian hoạt động: 9h30 - 24h từ thứ 2 - chủ nhật. Ngoài hotline CoffeeDev, các bạn có thể liên hệ qua Email hoặc Facebook của CoffeeDev</p>
				<a href="/" class="btn btn-primary py-md-3 px-md-5">Hỗ trợ</a>
				<a class="btn btn-secondary py-md-3 px-md-4 rounded-circle" href="/"><i class="fab fa-facebook-f"></i></a>
				<a class="btn btn-secondary py-md-3 px-md-4 rounded-circle" href="/"><i class="fab fa-linkedin-in"></i></a>
			</div>
			<div class="col-lg-4 col-md-6">
				<div class="service-item bg-light text-center p-5">
					<i class="fa fa-mug-hot display-1 text-primary mb-3"></i>
					<h4>Coffee</h4>
					<p class="mb-0">Cà phê ngon cũng giống như tình bạn: đậm đà, nồng ấm và bền chặt.</p>
				</div>
			</div>
			<div class="col-lg-4 col-md-6">
				<div class="service-item bg-light text-center p-5">
					<i class="fa fa-phone-alt display-1 text-primary mb-3"></i>
					<h4>Chăm sóc khách hàng</h4>
					<p class="mb-0">Website: coffeedev.com. Tổng đài Coffee Dev: 18006936. Hotline CSKH: 028 71 087 088.</p>
				</div>
			</div>
			<div class="col-lg-4 col-md-6">
				<div class="service-item bg-light text-center p-5">
					<i class="fa fa-truck display-1 text-primary mb-3"></i>
					<h4>Vận chuyển</h4>
					<div class="d-flex mb-2">
						<i class="bi bi-telephone text-black me-2"></i>
						<p class="mb-0">+84 098765432</p>
					</div>
					<div class="d-flex mb-2">
						<i class="bi bi-envelope-open text-white me-2"></i>
						<p class="mb-0">info@astems.co.kr</p>
					</div>
					<div class="d-flex mb-2">
						<i class="bi bi-geo-alt text-white me-2"></i>
						<p class="mb-0">Đường Tôn Đức Thắng, P.Bến Nghé, Quận 1,TP.HCM</p>
					</div>
				</div>
			</div>
			<div class="col-lg-4 col-md-6">
				<div class="service-item bg-light text-center p-5">
					<i class="fa fa-users display-1 text-primary mb-3"></i>
					<h4>Đội hỗ trợ</h4>
					<div class="d-flex mb-2">
						<i class="bi bi-telephone text-black me-2"></i>
						<p class="mb-0">+84 098765432 (A. Tính)</p>
					</div>
					<div class="d-flex mb-2">
						<i class="bi bi-telephone text-black me-2"></i>
						<p class="mb-0">+84 098765432 (A. Phong)</p>
					</div>
					<div class="d-flex mb-2">
						<i class="bi bi-envelope-open text-white me-2"></i>
						<p class="mb-0">info@astems.co.kr</p>
					</div>
					
				</div>
			</div>
			<div class="col-lg-4 col-md-6">
				<div class="service-item bg-light text-center p-5">
					<i class="fa fa-image display-1 text-primary mb-3"></i>
					<h4>Hình ảnh coffee</h4>
					<p class="mb-0">Hâm nóng tách cà phê của bạn bằng nồng nàn, hoặc đứng dậy ra đi chứ đừng uống nguội.</p>
				</div>
			</div>
		</div>
	</div>
</div>
<!-- Services End -->


<!-- Features Start -->
<div class="container-fluid bg-primary feature py-5 pb-lg-0 my-5">
	<div class="container py-5 pb-lg-0">
		<div class="mx-auto text-center mb-3 pb-2" style="max-width: 500px;">
			<h6 class="text-uppercase text-secondary">Coffee Dev</h6>
			<h1 class="display-5 text-white">The Grace Tower</h1>
		</div>
		<div class="row g-5">
			<div class="col-lg-3">
				<div class="text-white mb-5">
					<div class="bg-secondary rounded-pill d-flex align-items-center justify-content-center mb-3" style="width: 60px; height: 60px;">
						<i class="fa fa-seedling fs-4 text-white"></i>
					</div>
					<h4 class="text-white">100% Trái cà phê</h4>
					<p class="mb-0">Cùng Arabica, Robusta cũng là loại cà phê nổi tiếng được sử dụng phổ biến ở Việt Nam và nhiều nước khác trên thế giới. Với nhiều đặc điểm riêng, không...</p>
				</div>
				<div class="text-white">
					<div class="bg-secondary rounded-pill d-flex align-items-center justify-content-center mb-3" style="width: 60px; height: 60px;">
						<i class="fa fa-award fs-4 text-white"></i>
					</div>
					<h4 class="text-white">Chứng nhận chất lượng</h4>
					<p class="mb-0">Tại Ritachi Coffee chúng tôi luôn chú trọng đến quản trị tính đồng nhất, ổn định và chất lượng của mỗi sản phẩm mà chúng tôi gửi đến cho khách hàng.</p>
				</div>
			</div>
			<div class="col-lg-6">
				<div class="d-block bg-white h-100 text-center p-5 pb-lg-0">
					<p>Nhà mới Quận 7 toạ lạc tại The Grace Tower, thuộc khu phố nhộn nhiệp, sầm uất. Cửa hàng nổi bật với không gian nhỏ nhắn nhưng lại có nhiều nguồn sáng tự nhiên, mang đến sự hứng khởi, năng động</p>
					<img class="img-fluid" src={master1} alt="">
				</div>
			</div>
			<div class="col-lg-3">
				<div class="text-white mb-5">
					<div class="bg-secondary rounded-pill d-flex align-items-center justify-content-center mb-3" style="width: 60px; height: 60px;">
						<i class="fa fa-tractor fs-4 text-white"></i>
					</div>
					<h4 class="text-white">Đội hỗ trợ</h4>
					<div class="d-flex mb-2">
						<i class="bi bi-telephone text-black me-2"></i>
						<p class="mb-0">+84 098765432 (A. Tính)</p>
					</div>
					<div class="d-flex mb-2">
						<i class="bi bi-telephone text-black me-2"></i>
						<p class="mb-0">+84 098765432 (A. Phong)</p>
					</div>
					<div class="d-flex mb-2">
						<i class="bi bi-envelope-open text-white me-2"></i>
						<p class="mb-0">info@astems.co.kr</p>
					</div>
				</div>
				<div class="text-white">
					<div class="bg-secondary rounded-pill d-flex align-items-center justify-content-center mb-3" style="width: 60px; height: 60px;">
						<i class="fa fa-phone-alt fs-4 text-white"></i>
					</div>
					<h4 class="text-white"> Hỗ trợ 24/7</h4>
					<p class="mb-0">Website: coffeedev.com.<br/> Tổng đài Coffee Dev: 18006936.<br/> Hotline CSKH: 028 71 087 088.</p>
				</div>
			</div>
		</div>
	</div>
</div>
<!-- Features Start -->


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
	</div>
</div>
<!-- Products End -->

<!-- Team Start -->
<div class="container-fluid py-5">
	<div class="container">
		<div class="mx-auto text-center mb-5" style="max-width: 500px;">
			<h6 class="text-primary text-uppercase">Động đội</h6>
			<h1 class="display-5">Chúng tôi là lập trình viên chuyên nghiệp</h1>
		</div>
		<div class="row g-5">
			<div class="col-lg-4 col-md-6">
				<div class="row g-0">
					<div class="col-10">
						<div class="position-relative">
							<img class="img-fluid w-100" src={thien} alt="">
							<div class="position-absolute start-0 bottom-0 w-100 py-3 px-4" style="background: rgba(52, 173, 84, .85);">
								<h4 class="text-white">Nguyễn Thanh Thiên</h4>
								<span class="text-white">Back-End</span>
							</div>
						</div>
					</div>
					<div class="col-2">
						<div class="h-100 d-flex flex-column align-items-center justify-content-around bg-secondary py-5">
							<a class="btn btn-square rounded-circle bg-white" href="/"><i class="fab fa-twitter text-secondary"></i></a>
							<a class="btn btn-square rounded-circle bg-white" href="/"><i class="fab fa-facebook-f text-secondary"></i></a>
							<a class="btn btn-square rounded-circle bg-white" href="/"><i class="fab fa-linkedin-in text-secondary"></i></a>
							<a class="btn btn-square rounded-circle bg-white" href="/"><i class="fab fa-instagram text-secondary"></i></a>
						</div>
					</div>
				</div>
			</div>
			<div class="col-lg-4 col-md-6">
				<div class="row g-0">
					<div class="col-10">
						<div class="position-relative">
							<img class="img-fluid w-100" src={tinh} alt="">
							<div class="position-absolute start-0 bottom-0 w-100 py-3 px-4" style="background: rgba(52, 173, 84, .85);">
								<h4 class="text-white">Võ Đức Tính</h4>
								<span class="text-white">Database</span>
							</div>
						</div>
					</div>
					<div class="col-2">
						<div class="h-100 d-flex flex-column align-items-center justify-content-around bg-secondary py-5">
							<a class="btn btn-square rounded-circle bg-white" href="/"><i class="fab fa-twitter text-secondary"></i></a>
							<a class="btn btn-square rounded-circle bg-white" href="/"><i class="fab fa-facebook-f text-secondary"></i></a>
							<a class="btn btn-square rounded-circle bg-white" href="/"><i class="fab fa-linkedin-in text-secondary"></i></a>
							<a class="btn btn-square rounded-circle bg-white" href="/"><i class="fab fa-instagram text-secondary"></i></a>
						</div>
					</div>
				</div>
			</div>
			<div class="col-lg-4 col-md-6">
				<div class="row g-0">
					<div class="col-10">
						<div class="position-relative">
							<img class="img-fluid w-100" src={phong} alt="">
							<div class="position-absolute start-0 bottom-0 w-100 py-3 px-4" style="background: rgba(52, 173, 84, .85);">
								<h4 class="text-white">Đặng Hoài Phong</h4>
								<span class="text-white">Front-End</span>
							</div>
						</div>
					</div>
					<div class="col-2">
						<div class="h-100 d-flex flex-column align-items-center justify-content-around bg-secondary py-5">
							<a class="btn btn-square rounded-circle bg-white" href="/"><i class="fab fa-twitter text-secondary"></i></a>
							<a class="btn btn-square rounded-circle bg-white" href="/"><i class="fab fa-facebook-f text-secondary"></i></a>
							<a class="btn btn-square rounded-circle bg-white" href="/"><i class="fab fa-linkedin-in text-secondary"></i></a>
							<a class="btn btn-square rounded-circle bg-white" href="/"><i class="fab fa-instagram text-secondary"></i></a>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
<!-- Team End -->


