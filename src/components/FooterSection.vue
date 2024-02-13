<script></script>
<template>
  <div class="bg-container">
    <div class="footer-container">
      <div class="link-container">
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
  </div>
</template>

<style scoped>
h3 {
  font-size: 1.6rem;
  margin-bottom: 1.5rem;
  font-weight: 600;
}
li {
  font-size: 1.2rem;
  margin-bottom: 0.5rem;
}
.bg-container {
  max-width: 100%;
  background-color: hsl(240, 10%, 16%);
  border-top-right-radius: 65px;
}
img {
  width: 85px;
  height: 30px;
}
.footer-container {
  width: 70rem;
  color: white;
  display: flex;
  margin: 0 auto;
  justify-content: space-between;
  padding: 7rem 0 6rem 0;
}
.link-container {
  width: 100%;
  display: flex;
  justify-content: space-between;
}
.links {
  display: flex;
  flex-direction: column;
}
@media only screen and (max-width: 875px) {
  .link-container {
    flex-direction: column;
    margin: auto;
    width: 10rem;
  }
  img {
    margin-bottom: 4rem;
  }
  h3,
  ul {
    margin-bottom: 2rem;
  }
}
</style>
