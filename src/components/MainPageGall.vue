<template>
    <div class="back-main-gal">
        <div class="container container-main">
            <div class="row">
                <div class="col text-center">
                    <div class="textname">
                        Борщевик Борщевик Борщевик   
                    </div>
                </div>
            </div>
            <div class="row col-block">
                <div class="col-md-6 ">
                    
                    <img src="../assets/photo_2022-12-11_17-12-51.jpg" alt="Image 1" style="max-width: 100%;">
                    <p>Text for image 1</p>
                </div>
                <div class="col-md-6">
                    <img src="../assets/photo_2022-12-11_17-12-51.jpg" alt="Image 2" style="max-width: 100%;">
                    <p>Text for image 2</p>
                </div>
            </div>
            <div class="row">
                <div class="col-md-6">
                    <img src="../assets/photo_2022-12-11_17-12-51.jpg" alt="Image 3" style="max-width: 100%;">
                    <p>Text for image 3</p>
                </div>
                <div class="col-md-6">
                    <img src="../assets/photo_2022-12-11_17-12-51.jpg" alt="Image 4" style="max-width: 100%;">
                    <p>Text for image 4</p>
                </div>
            </div>
            <div class="row">
                <div class="col text-center">
                    <div class="line">
                        
                    </div>
                </div>
            </div>
            <swiper
                :slides-per-view="3"
                :space-between="50"
                navigation
                :pagination="{ clickable: true }"
                @swiper="onSwiper"
                @slideChange="onSlideChange"
            >
                <swiper-slide>
                <h2>Slide 1</h2>
                <p>--------</p>
                <p>--------</p>
                <p>--------</p>
                <p>--------</p>
                </swiper-slide>
                <swiper-slide>
                <h2>Slide 2</h2>
                </swiper-slide>
                <swiper-slide>
                <h2>Slide 3</h2>
                </swiper-slide>
                <swiper-slide>
                <h2>Slide 4</h2>
                </swiper-slide>
                <swiper-slide>
                <h2>Slide 5</h2>
                </swiper-slide>
                <swiper-slide>
                <h2>Slide 6</h2>
                </swiper-slide>
            </swiper>
        </div>
    </div>
</template>
<script>

</script>
<style>
.back-main-gal{
    background-image: url(../assets/back.png);
    width: 100%;
    height: 1853px;

}


.textname {
    color: white;
    font-size: 40px;
}
.line{
    border-bottom: 2px solid rgb(255, 255, 255);
    width: 100%;
    width: 100%;
    height: 100px;
    box-sizing: border-box;
    padding: 20px;
    border-top-left-radius: 30px; /* задайте радиус для левого верхнего угла */
    border-top-right-radius: 30px; /* задайте радиус для правого верхнего угла */
}
</style>

