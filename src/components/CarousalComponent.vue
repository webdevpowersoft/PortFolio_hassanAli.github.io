<template>
  <Carousel class="gt-xs" :itemsToShow="3.95" :wrapAround="true" :transition="500">
    <Slide v-for="slide in item" :key="slide">
      <q-img :src="slide.src">
        <!-- <div class="text-h6 text-center absolute-bottom">{{slide.name}}</div> -->
      </q-img>
      <!-- <div class="carousel__item">{{ slide.title }}</div> -->
    </Slide>

    ...
  </Carousel>
  <Carousel class="lt-sm" :itemsToShow="1.50" :wrapAround="true" :transition="500">
    <Slide v-for="slide in item" :key="slide">
      <q-img :src="slide.src" style="height: 380px">
        <!-- <div class="text-h6 text-center absolute-bottom">{{slide.name}}</div> -->
      </q-img>
      <!-- <div class="carousel__item">{{ slide.title }}</div> -->
    </Slide>

    ...
  </Carousel>
</template>

<script>
import { defineComponent } from 'vue'
import { Carousel, Pagination, Slide } from 'vue3-carousel'

import 'vue3-carousel/dist/carousel.css'

export default defineComponent({
  name: 'Autoplay',
  components: {
    Carousel,
    Slide,
    Pagination,
  },
  setup() {
    return {
      item: [
        {
          src: require("assets/hassanpic.jpeg"),
          // name:"Hassan Ali"
        },
        {
          src: require("assets/ahmd.jpg"),
          // name:"Zohaib Ahmad"
        },
        {
          src: require("assets/azhar.jpg"),
          // name:"Muhammad Azhar"
        },
        {
          src: require("assets/picture2.jpg"),
          // name:"Muhammad Maaz"
        },
      ]
    }
  }
})
</script>

<style scoped>
.carousel__slide {
  padding: 5px;
}

.carousel__viewport {
  perspective: 2000px;
}

.carousel__track {
  transform-style: preserve-3d;
}

.carousel__slide--sliding {
  transition: 0.5s;
}

.carousel__slide {
  opacity: 0.9;
  transform: rotateY(-20deg) scale(0.9);
}

.carousel__slide--active~.carousel__slide {
  transform: rotateY(20deg) scale(0.9);
}

.carousel__slide--prev {
  opacity: 1;
  transform: rotateY(-10deg) scale(0.95);
}

.carousel__slide--next {
  opacity: 1;
  transform: rotateY(10deg) scale(0.95);
}

.carousel__slide--active {
  opacity: 1;
  transform: rotateY(0) scale(1.1);
}
</style>
