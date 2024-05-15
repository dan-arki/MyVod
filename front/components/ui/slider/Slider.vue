<script setup>
import "vue3-carousel/dist/carousel.css";
import { Carousel, Slide, Pagination, Navigation } from "vue3-carousel";
</script>

<template>
  <section class="carousel-container">
    <UiHeader></UiHeader>
    <Carousel
      :items-to-show="1"
      :navigation-enabled="true"
      :pagination-enabled="true"
      :wrap-around="true"
      class="h-fit w-full"
    >
      <Slide v-for="video in videos" :key="video.id" class="h-full">
        <video class="w-full h-full object-cover" autoplay muted loop>
          <source :src="video.src" type="video/mp4" />
          Your browser does not support the video tag.
        </video>
      </Slide>

      <!-- <template #addons>
        <Navigation />
        <Pagination />
      </template> -->
    </Carousel>
  </section>
</template>

<script>
export default {
  data() {
    return {
      videos: [
        { id: 1, src: "omerVideo.mp4" },
        // { id: 2, src: "omerVideo.mp4" },
        // { id: 2, src: "danVideoParc.mp4" },
      ],
    };
  },
};
</script>

<style scoped>
.carousel-container {
  width: 100%;
  height: fit-content;
  padding: 0;
  position: relative;
}

.carousel-container .carousel {
  height: fit-content;
}

.carousel-container .carousel .slide {
  display: flex;
  align-items: center;
  justify-content: center;
  height: fit-content;
}

video {
  width: 100%;
  height: 100%;
  max-height: 100vh;
  object-fit: cover;
}
</style>
