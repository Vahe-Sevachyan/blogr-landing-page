<script></script>
<template>
  <div class="wrapper">
    <img src="../assets/images/illustration-laptop-desktop.svg" alt="" />
    <div class="content-container">
      <div>
        <h3>Free, Open, Simple</h3>
        <p>
          Blogr is a free and open source application backed by a large
          community of helpful developers. It supports features such as code
          syntax nighlignting, kos teeds, social medla integration, third-party
          commenting tools, and works seamlessly with Google Analytics. The
          architecture is clean and is relatively easy to learn.
        </p>
      </div>
      <div>
        <h3>Powerful tooling</h3>
        <p>
          Batteries included. We built a simple and straighttorward CLI tool
          that makes customization and deployment a breeze, but capable of
          producing even the most complicated sites.
        </p>
      </div>
    </div>
  </div>
</template>
<style scoped>
.wrapper {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin: auto;
  width: 140rem;
  margin-top: 12rem;
  transform: translateX(-345px);
}
.content-container {
  width: 60rem;
}
p {
  color: hsl(208, 46%, 35%);
  font-size: 1.8rem;
  margin-bottom: 3rem;
}
h3 {
  color: hsl(208, 46%, 35%);
  font-size: 3rem;
  margin-bottom: 3rem;
}
img {
  width: 650px;
  height: 690px;
  /* transform: translateX(-345px); */
  object-fit: cover;
}
</style>
