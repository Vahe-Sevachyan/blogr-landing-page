<script>
export default {
  name: "NavBar",
};
</script>

<template>
  <div class="nav-section">
    <nav class="nav-menu">
      <img src="../assets/images/logo.svg" alt="blog logo" />
      <ul class="nav-links">
        <li>Product</li>
        <li>Category</li>
        <li>Contact</li>
      </ul>
    </nav>

    <div class="btn-container">
      <button>Login</button>
      <button>Sign Up</button>
    </div>
  </div>
</template>

<style scoped>
.nav-section {
  /* background-color: grey; */
  /* width: 130rem; */
  width: 80%;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;

  padding: 1.5rem 1rem 1.5rem 1rem;
}
.nav-menu {
  display: flex;
  width: 33rem;
  justify-content: space-between;
}
.nav-links {
  display: flex;
  width: 18rem;
  justify-content: space-between;
  list-style: none;
  align-items: center;
}
.btn-container {
  width: 12rem;
  display: flex;
  justify-content: space-between;
}
</style>
