<script>
export default {
  name: "NavBar",
};
</script>

<template>
  <div class="nav-section">
    <div class="nav-menu">
      <img src="../assets/images/logo.svg" alt="blog logo" />
      <ul class="nav-links">
        <li>Product</li>
        <li>Category</li>
        <li>Contact</li>
      </ul>
    </div>

    <div class="btn-container">
      <button>Login</button>
      <button>Sign Up</button>
    </div>
  </div>
</template>

<style scoped>
.nav-section {
  background-color: grey;
  width: 90rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.nav-menu {
  display: flex;
  width: 23rem;
  justify-content: space-between;
}
.nav-links {
  display: flex;
  width: 40rem;
  justify-content: space-between;
  list-style: none;
}
.btn-container {
  width: 10rem;
  display: flex;
  justify-content: space-between;
}
</style>
