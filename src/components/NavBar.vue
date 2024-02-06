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
      <button class="btn-one">Login</button>
      <button class="btn-two">Sign Up</button>
    </div>
  </div>
</template>

<style scoped>
button {
  font-family: "Ubuntu", Arial, Helvetica, sans-serif, monospace;
  font-weight: 600;
  cursor: pointer;
  padding: 1rem 1.5rem 1rem 1.5rem;
  border: none;
  border-radius: 20px;
  /* border: solid white 1.5px; */
}
.nav-section {
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
  width: 20rem;
  justify-content: space-between;
  list-style: none;
  align-items: center;
  font-family: "Ubuntu", Arial, Helvetica, sans-serif, monospace;
  font-size: 1.5rem;
  color: white;
}
.btn-container {
  width: 17rem;
  display: flex;
  justify-content: space-between;
}
.btn-two {
  color: hsl(356, 100%, 66%);
}
.btn-one {
  color: white;
  background-color: inherit;
}
</style>
