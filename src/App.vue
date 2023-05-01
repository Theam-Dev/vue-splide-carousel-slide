<template>
  <splide>
  <splide-slide>
    <img src="@/assets/img/p1.jpg">
  </splide-slide>
  <splide-slide>
    <img src="@/assets/img/p2.jpg">
  </splide-slide>
  <splide-slide>
    <img src="@/assets/img/p3.jpg">
  </splide-slide>
</splide>
</template>

<script>
import '@splidejs/splide/dist/css/themes/splide-default.min.css';
import '@splidejs/splide/dist/css/themes/splide-sea-green.min.css';
import '@splidejs/splide/dist/css/themes/splide-skyblue.min.css';

import { Splide, SplideSlide } from '@splidejs/vue-splide';
export default {
  name: 'App',
  components: {
    Splide,
    SplideSlide,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
