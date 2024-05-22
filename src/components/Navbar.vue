<template>
  <nav>
    <div class="logo"><b>TOM'S CAKE</b></div>
    <ul>
      <li><a href="#home">HOME</a></li>
      <li><a href="#products">PRODUCTS</a></li>
      <li><a href="#contact">CONTACT</a></li>
      <li class="cart">
        <a href="#cart">
          <i class="fas fa-shopping-cart"></i>
        </a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 20px;
  background-color: #613613;
  color: #fff;
  width: 100%;
  position: fixed;
  top: 0;
  left: 0;
  z-index: 1000;
}
nav .logo {
  font-size: 1.5em;
}
nav ul {
  display: flex;
  list-style: none;
  margin: 0;
  padding: 0;
  margin-right: 20px;
}
nav ul li {
  margin: 0 10px;
}
nav ul li a {
  color: #fff;
  text-decoration: none;
}
nav ul li.cart a {
  display: flex;
  align-items: center;
}
nav ul li.cart i {
  font-size: 1.2em; /* Adjust the size of the cart icon */
}
</style>
