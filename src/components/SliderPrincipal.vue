<template>
    <div id="myCarousel" class="carousel slide mb-6" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item" v-for="(item, index) in slider" :key="index" :class="{ 'active': index === 0 }">
                <div class="bd-placeholder-img">
                    <img :src="item.BackgroundImage">
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
                    BackgroundImage: require('../assets/imagens/IMG_20191011_105943958-1920x1080.jpg'), 
                },
                {
                    BackgroundImage: require('../assets/imagens/IMG_20191011_105854935-1920x1080.jpg'), 
                },
                {
                    BackgroundImage: require('../assets/imagens/IMG_20191011_112031712-1920x1080.jpg'), 
                },
            ]
        }
    }
}
</script>