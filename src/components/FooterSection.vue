<script></script>
<template>
  <div class="bg-container">
    <div class="nav-container">
      <img src="../assets/images/logo.svg" alt="logo picture" />
      <div class="link-container">
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
  </div>
</template>

<style scoped>
.bg-container {
  max-width: 100%;
  background-color: black;
}
img {
  width: 85px;
  height: 30px;
}
.nav-container {
  /* height: 30vh; */
  width: 60rem;
  color: white;
  display: flex;
  margin: 0 auto;
  justify-content: space-between;
  padding: 7rem 0 7rem 0;
}
.link-container {
  width: 40rem;
  display: flex;
  justify-content: space-between;
}
.links {
  display: flex;
  flex-direction: column;
}
</style>
