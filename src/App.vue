<template>
  <div id="app">
    <Navbar />
    <Carousel />
    <div class="card-container">
      <Card
        title="Red Velvet Cake"
        description="Rp.120.000"
        image="https://funcakes.com/content/uploads/2021/02/Red-Velvet-Cake-with-Fruit-960x720-c-default.jpg"
      />
      <Card
        title="Black Forest Cake"
        description="Rp.140.000"
        image="https://www.foodandwine.com/thmb/H9NS3GaVp-2XHt6wbPtrhwh0bws=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/Black-Forest-Cake-FT-RECIPE0623-29bb291902e845bab17a7fc1d65e4ebb.jpg"
      />
      <Card
        title="Easter Sheet Cakes"
        description="Rp.100.000"
        image="https://www.southernliving.com/thmb/emcsns4kPShh23jSRvE2BOD0UAg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/Southern-Living_27201_EasterSheetCakes_0079-2e125f1c3daf4495a379065c11b2cf21.jpg"
      />
    </div>
    <div class="card-container">
      <Card
        title="Naked Cake"
        description="Rp.100.000"
        image="https://preppykitchen.com/wp-content/uploads/2022/05/Naked-Cake-Recipe-Card.jpg"
      />
      <Card
        title="Chocolate Pinata Cake"
        description="Rp.120.000"
        image="https://assets-eu-01.kc-usercontent.com/559bb7d3-88a4-01c1-79a3-dd4d5b2d2bb0/1d45a717-bf86-424c-9646-ca7d3b34e614/Chocolate%20Pinata%20Cake_Landscape-13.jpg"
      />
      <Card
        title="Pinata Rainbow Cake"
        description="Rp.120.000"
        image="https://recipesblob.oetker.co.uk/assets/46b664a502ce4ebdb241e6667ce789b7/1272x764/pinata-rainbow-cake.webp"
      />
    </div>
    <Footer />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Carousel from "./components/Carousel.vue";
import Card from "./components/Card.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Carousel,
    Card,
    Footer,
  },
};
</script>

<style>
.card-container {
  display: flex;
  justify-content: space-around;
  margin: 20px 0;
}
</style>
