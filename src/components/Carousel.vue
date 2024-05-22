<template>
  <div class="carousel">
    <div class="carousel-item" v-for="(image, index) in images" :key="index">
      <img :src="image" alt="carousel image" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Carousel",
  data() {
    return {
      images: [
        "https://marketplace.canva.com/EAFFpe5PVN4/1/0/1600w/canva-black-brown-minimalist-aesthetic-modern-grand-opening-soft-cake-banner-1QK0IS-7sD0.jpg",
        "https://media.istockphoto.com/id/1044980744/id/foto/donat.jpg?s=2048x2048&w=is&k=20&c=OJ9B37-507GaV6ijRgoyWrS6ZbPHqAHM2YmZefrPk8g=",
        "https://www.southernliving.com/thmb/emcsns4kPShh23jSRvE2BOD0UAg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/Southern-Living_27201_EasterSheetCakes_0079-2e125f1c3daf4495a379065c11b2cf21.jpg",
      ],
    };
  },
};
</script>

<style>
.carousel {
  display: flex;
  overflow: auto;
  width: 100%;
}

.carousel-item {
  min-width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 500px; /* Ubah sesuai kebutuhan */
  width: 100%;
}

.carousel-item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
</style>
