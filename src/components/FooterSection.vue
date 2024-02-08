<script></script>
<template>
  <div class="container">
    <div class="nav-container">
      <img src="../assets/images/logo.svg" alt="logo picture" />
      <div class="links">
        <h3>Product</h3>
        <ul>
          <li>Overview</li>
          <li>Pricing</li>
          <li>Marketplace</li>
          <li>Features</li>
          <li>Integrations</li>
        </ul>
      </div>
      <div class="links">
        <h3>Company</h3>
        <ul>
          <li>About</li>
          <li>Team</li>
          <li>Blog</li>
          <li>Careers</li>
        </ul>
      </div>
      <div class="links">
        <h3>Connect</h3>
        <ul>
          <li>Contact</li>
          <li>Newsletter</li>
          <li>Linkedin</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  max-width: 100%;
}
img {
  width: 85px;
  height: 30px;
}
.nav-container {
  background-color: black;
  height: 30vh;
  width: 80%;
  color: white;
  display: flex;
}
.links {
  display: flex;
  flex-direction: column;
}
</style>
