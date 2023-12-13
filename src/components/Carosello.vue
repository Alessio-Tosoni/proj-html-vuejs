<template>
    <swiper :spaceBetween="30" :autoplay="{
        delay: 3500,
        disableOnInteraction: false,
    }" :pagination="{
    clickable: true,
}" :navigation="true" :modules="modules" class="mySwiper">

        <!-- slide  1 -->
        <swiper-slide>
            <img src="\assets\slider1-1.jpg" alt="">
        </swiper-slide>

        <!--slide 2  -->
        <swiper-slide>
            <img src="\assets\slider2-1.jpg" alt="">
        </swiper-slide>

        <!-- slide 3 -->
        <swiper-slide>
            <img src="\assets\slider3.jpg" alt="">
        </swiper-slide>

        <!-- slide 4 -->
        <swiper-slide>
            <img src="\assets\slider4.jpg" alt="">
        </swiper-slide>


    </swiper>
</template>
<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue';

// Import Swiper styles
import 'swiper/css';

import 'swiper/css/pagination';
import 'swiper/css/navigation';



// import required modules
import { Autoplay, Pagination, Navigation } from 'swiper/modules';

export default {
    components: {
        Swiper,
        SwiperSlide,
    },
    setup() {
        return {
            modules: [Autoplay, Pagination, Navigation],
        };
    },
};
</script>
<style scoped>
.swiper {
    width: 70%;
    height: 10%;
}

.swiper-slide {
    text-align: center;
    font-size: 18px;
    background: #fff;

    /* Center slide text vertically */
    display: flex;
    justify-content: center;
    align-items: center;
}

.swiper-slide img {
    display: block;
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.swiper {
    margin-left: auto;
    margin-right: auto;
}
</style>