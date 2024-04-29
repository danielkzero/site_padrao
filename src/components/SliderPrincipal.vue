<template>
    <div id="myCarousel" class="carousel slide " data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item" v-for="(item, index) in slider" :key="index" :class="{ 'active': index === 0 }">
                <div class="bd-placeholder-img slider" :style="{ 'background-image': 'url(' + item.BackgroundImage + ')' }">
                </div>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#myCarousel" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Anterior</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#myCarousel" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Próximo</span>
        </button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            slider: [
            {
                    BackgroundImage: require('../assets/imagens/1024x576/home01-1024x576.jpg')
                },
                {
                    BackgroundImage: require('../assets/imagens/1024x576/home02-1024x576.jpg')
                },
                {
                    BackgroundImage: require('../assets/imagens/1024x576/home03-1024x576.jpg')
                },
                {
                    BackgroundImage: require('../assets/imagens/1024x576/home04-1024x576.jpg')
                },
                {
                    BackgroundImage: require('../assets/imagens/1024x576/home05-1024x576.jpg')
                },
                {
                    BackgroundImage: require('../assets/imagens/1024x576/home06-1024x576.jpg')
                },
                {
                    BackgroundImage: require('../assets/imagens/1024x576/home07-1024x576.jpg')
                },
                {
                    BackgroundImage: require('../assets/imagens/1024x576/home08-1024x576.jpg')
                },
            ]
        }
    }
}
</script>
<style>
.slider {
    height: 700px;
    background-repeat: no-repeat;
    background-size: 100% auto;
    background-position: center center;
}
.carousel-item {
        height: auto !important;
    }

@media only screen and (max-width: 1024px) {
    .slider {
        height: 576px !important;
        background-size: auto 100% !important;
        background-color: rgb(11, 50, 63);
    }
    .carousel-item {
        height: auto !important;
    }
}
@media only screen and (max-width: 600px) {
    .slider {
        height: 400px !important;
        background-color: lightblue;
    }
    .carousel-item {
        height: auto !important;
    }
}




</style>