<template>
    <div class="container container-main">
        <slot>
            <div class="row">
                <div class="col text-center">
                    <div class="logo">
                        <img src="@/assets/logo.png" alt="">
                    </div>
                 </div>
                <div class="col text-center">
                    <div class="textlogo">
                        <a>Борщевик</a>    
                    </div>
              </div>
            </div>
            <div class="row">
                <div class="col text-center">
                        <a>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum</a>
                </div>
            </div>
            <div class="row">
                <div class="col text-center">
                    <button type="button" class="btn btn-primary">Скачать</button>
                </div>
            </div>
            <div class="row">
                <div class="col text-center">
                    <img src="@/assets/icon_people.png" alt="">
                </div>
                <div class="col text-center">
                    <img src="@/assets/icon_people.png" alt="">
                </div>
                <div class="col text-center">
                    <img src="@/assets/icon_people.png" alt="">
                </div>
            </div>
            <div class="row">
                <div class="col text-center">
                    <div class="line">
                        
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col text-center">
                    <div class="textlogo2">
                        <a>Борщевик Борщевик Борщевик</a>    
                    </div>
                </div>
                <div class="col text-center">
                    <div class="logocol">
                        <img src="@/assets/photo_2022-12-11_17-12-51.jpg" alt="">
                    </div>
                 </div>
            </div>
        </slot>
    </div>
</template>

<style lang="scss">
.logo img{
    width: 100px;
    height: 100px;
  }
.logoText{
    width: 100%;
    max-width: 960px;
    margin: 0 auto;
    color: white;
  
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
.textlogo{
    font-size: 25px;
}
.textlogo2{
    font-size: 48px;
}

</style>