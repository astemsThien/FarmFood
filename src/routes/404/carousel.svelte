<script>
	import coffee from '../img/bg-coffee.png';
</script>

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