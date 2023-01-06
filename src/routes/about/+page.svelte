<script>
	import coffee1 from '../img/coffee-1.png'

</script>

<svelte:head>
	<title>Giới thiệu</title>
	<meta name="description" content="About this app" />
</svelte:head>

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

