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
  width: 100%;
  /* width: 140rem; */
  margin-top: 12rem;
  transform: translateX(-125px);
  margin-bottom: 10rem;
}
.content-container {
  width: 40%;
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
  width: 750px;
  height: 790px;
  /* transform: translateX(-345px); */
  object-fit: cover;
  padding-right: 5rem;
}

@media only screen and (max-width: 1250px) {
  p {
    font-size: 1.3rem;
  }
  h3 {
    font-size: 2rem;
  }
  img {
    width: 650px;
    height: 690px;
  }
  @media only screen and (max-width: 875px) {
    .wrapper {
      flex-direction: column;
      transform: translateX(30px);

      margin: auto;
    }
    img {
      width: 550px;
      height: 590px;
      object-fit: contain;
    }
  }
  .content-container {
    display: flex;
    flex-direction: column;
  }
}
</style>
