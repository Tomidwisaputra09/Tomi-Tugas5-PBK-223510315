<template>
  <footer>
    <p>&copy; 2024 My Online Store. All rights reserved.</p>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
footer {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #292827;
  color: #fff;
  padding: 0px 0px;
  position: fixed;
  width: 100%;
  height: 40px;
  bottom: 0;
  left: 0;
  z-index: 1000;
}
</style>
