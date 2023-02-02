<script>
  /** @type {import('./$types').PageData} */
  export let data;

  import "$lib/style.css";

  // import function to register Swiper custom elements
  import { register } from "swiper/element/bundle";
  // register Swiper custom elements
  register();
</script>

<swiper-container
  class="mySwiper"
  pagination="true"
  effect="cube"
  grab-cursor="true"
  cube-effect-shadow="true"
  cube-effect-slide-shadows="true"
  cube-effect-shadow-offset="20"
  cube-effect-shadow-scale="0.94"
>
  <swiper-slide>
    <img src=" https://swiperjs.com/demos/images/nature-1.jpg" />
  </swiper-slide>
  <swiper-slide>
    <img src="https://swiperjs.com/demos/images/nature-2.jpg" />
  </swiper-slide>
  <swiper-slide>
    <img src="https://swiperjs.com/demos/images/nature-3.jpg" />
  </swiper-slide>
  <swiper-slide>
    <img src="https://swiperjs.com/demos/images/nature-4.jpg" />
  </swiper-slide>
</swiper-container>
