<script>
	import Header from './login-signup/+page.svelte';
	import Carousel from './404/carousel.svelte';
    import {cart} from './product/card.js';
    import Name from './404/marqee.svelte';
	import coffee from './img/bg-coffee.png';

</script>

<header>
	<!-- Topbar Start -->
    <div class="container-fluid px-5 d-none d-lg-block">
        <div class="row gx-5 py-3 align-items-center">
            <div class="col-lg-3">
                <div class="d-flex align-items-center justify-content-start">
                    <i class="bi bi-phone-vibrate fs-1 text-primary me-2"></i>
                    <h2 class="mb-0">+84 98765432</h2>
                </div>
            </div>
            <div class="col-lg-6">
                <div class="d-flex align-items-center justify-content-center">
                    <a href="index.html" class="navbar-brand ms-lg-5">
                        <h1 class="m-0 display-4 text-primary"><span class="text-secondary">Coffee</span>Dev</h1>
                    </a>
                </div>
            </div>
            <div class="col-lg-3">
                <div class="d-flex align-items-center justify-content-end">
                    <a href="/login-signup" class="nav-item nav-link btn py-md-3 px-md-4">Đăng nhập</a>
                    <a class="btn btn-secondary py-md-3 px-md-4 rounded-circle" href="/cart"><i class="fas fa-shopping-cart">({$cart.length})</i></a>
                    <!-- <a class="btn btn-secondary py-md-3 px-md-4 rounded-circle" href="/"><i class="fab fa-facebook-f"></i></a>
                    <a class="btn btn-secondary py-md-3 px-md-4 rounded-circle" href="/"><i class="fab fa-linkedin-in"></i></a>
                    <a class="btn btn-secondary py-md-3 px-md-4 rounded-circle" href="/"><i class="fab fa-instagram"></i></a> -->
                </div>
            </div>
        </div>
		<marquee><Name/></marquee>

    </div>
    <!-- Topbar End -->


    <!-- Navbar Start -->
    <nav class="navbar navbar-expand-lg bg-primary navbar-dark shadow-sm py-3 py-lg-0 px-3 px-lg-5">
        <a href="index.html" class="navbar-brand d-flex d-lg-none">
            <h1 class="m-0 display-4 text-secondary"><span class="text-white">Coffee</span>Dev</h1>
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse " id="navbarCollapse">
            <div class="navbar-nav mx-auto py-0">
                <a href="/" class="nav-item nav-link">Trang chủ</a>
                <a href="/about" class="nav-item nav-link">Giới thiệu</a>
                <a href="/servicess" class="nav-item nav-link">Dịch vụ</a>
                <a href="/product" class="nav-item nav-link">Sản phẩm</a>
                <div class="nav-item dropdown">
                    <a href="/" class="nav-link dropdown-toggle" data-bs-toggle="dropdown">Loại Coffee</a>
                    <div class="dropdown-menu m-0">
						<a href="/" class="dropdown-item">Coffee Arabica</a>
						<a href="/" class="dropdown-item">Coffee Cherry</a>
                        <a href="/" class="dropdown-item">Coffee Moka</a>
                        <a href="/" class="dropdown-item">Coffee Robusta</a>
                        <a href="/" class="dropdown-item">Coffee Culi</a>
                    </div>
                </div>
                <a href="/contact" class="nav-item nav-link">Liên hệ</a>
                <!-- <a href="/" class="nav-item nav-link" style="margin-left: 50px;"><i class="fas fa-shopping-cart"></i></a> -->
            </div>
        </div>
    </nav>
    <!-- Navbar End -->
    <!-- Carousel Start -->
        <!-- <Carousel /> -->

        <div class="container-fluid p-0">
            <div id="header-carousel" class="carousel slide carousel-fade" data-bs-ride="carousel">
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img class="w-100" src={coffee} alt="">
                        <div class="carousel-caption top-0 bottom-0 start-0 end-0 d-flex flex-column align-items-center justify-content-center">
                            <div class="text-start p-5" style="max-width: 900px;">
                                <h3 class="text-white">Coffee giống như tình bạn:</h3>
                                <h1 class="display-1 text-white mb-md-4">Đậm đà, nồng ấm và bền chặt</h1>
                                <a href="/" class="btn btn-primary py-md-3 px-md-5 me-3">Chi tiết</a>
                                <a href="/" class="btn btn-secondary py-md-3 px-md-5">Liên hệ</a>
                            </div>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <img class="w-100" src={coffee} alt="">
                        <div class="carousel-caption top-0 bottom-0 start-0 end-0 d-flex flex-column align-items-center justify-content-center">
                            <div class="text-start p-5" style="max-width: 900px;">
                                <h3 class="text-white">Coffee giống như tình yêu:</h3>
                                <h1 class="display-1 text-white mb-md-4">Ban đầu thấy đắng, sau ngọt ngào</h1>
                                <a href="/" class="btn btn-primary py-md-3 px-md-5 me-3">Chi tiêt</a>
                                <a href="/" class="btn btn-secondary py-md-3 px-md-5">Liên hệ</a>
                            </div>
                        </div>
                    </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#header-carousel"data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#header-carousel"data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
            </div>
        </div>
    <!-- Carousel End -->
</header>
