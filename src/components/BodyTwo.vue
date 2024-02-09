<script></script>
<template>
  <div class="main-container">
    <div class="display-container">
      <div class="img-container">
        <img src="../assets/images/illustration-phones.svg" alt="" />
      </div>

      <div class="paragraph-container">
        <h1>State of the art infrastructure</h1>
        <p>
          With reliability and speed in mind. worldwide data centers provide the
          backbone for ultra-fast connectivity. This ensures your site will load
          instantly, no matter where your readers are, keeping your site
          competitive.
        </p>
      </div>
    </div>
  </div>
</template>
<style scoped>
.main-container {
  background-color: hsl(237, 17%, 21%);
  align-items: center;
  width: 100%;
  margin: auto;
  border-bottom-left-radius: 185px;
  border-top-right-radius: 185px;
}
.display-container {
  display: flex;
  align-items: center;
  width: 70vw;
  margin: auto;
  /* text-align: left; */
  background-image: url("../assets/images/bg-pattern-circles.svg");
  background-repeat: no-repeat;
  background-position-y: top;
  justify-content: space-between;
}
/* .img-container {
  background-image: url("../assets/images/bg-pattern-circles.svg");
  background-position-x: left;
  background-size: cover;
} */
.paragraph-container {
  display: flex;
  flex-direction: column;
  width: 30vw;
  color: white;
}
.paragraph-container h1 {
  font-size: 3.8em;
  margin-bottom: 1.5rem;
}
p {
  font-size: 2em;
  color: white;
}
</style>
