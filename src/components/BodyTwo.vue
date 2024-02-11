<script></script>
<template>
  <div class="main-container">
    <div class="display-container">
      <!-- <div class="img-container">
        <img src="../assets/images/illustration-phones.svg" alt="" />
      </div> -->
      <img src="../assets/images/illustration-phones.svg" alt="" />
      <div class="paragraph-container">
        <h3>State of the art infrastructure</h3>
        <p>
          With reliability and speed in mind. worldwide data centers provide the
          backbone for ultra-fast connectivity. This ensures your site will load
          instantly, no matter where your readers are, keeping your site
          competitive. Keeping your site competitive.
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
  border-bottom-left-radius: 145px;
  border-top-right-radius: 145px;
  background-image: url("../assets/images/bg-pattern-circles.svg");
  background-repeat: no-repeat;
  justify-content: space-between;
  height: 50rem;
}
.display-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 68vw;
  margin: auto;
}
img {
  width: 650px;
  height: 690px;
  object-fit: cover;
  transform: translateY(-65px);
}
/* .img-container {
  background-image: url("../assets/images/bg-pattern-circles.svg");
  background-position-x: left;
  background-size: cover;
} */
.paragraph-container {
  display: flex;
  flex-direction: column;
  margin-bottom: 18rem;
  width: 30vw;
  color: white;
  font-size: 8px;
}
.paragraph-container h3 {
  font-size: 3.8em;
  margin-bottom: 1.5rem;
}
p {
  font-size: 2em;
  color: white;
}
@media only screen and (max-width: 1525px) {
  .paragraph-container {
    font-size: 7px;
  }
  img {
    width: 550px;
    height: 590px;
  }
  .main-container {
    height: 45rem;
  }
}
@media only screen and (max-width: 1250px) {
  .paragraph-container {
    font-size: 6px;
  }
  .main-container {
    height: 40rem;
  }
}
@media only screen and (max-width: 875px) {
  .display-container {
    flex-direction: column;
  }
  .main-container {
    height: 60rem;
  }
  img {
    margin-bottom: -20rem;
    transform: translateY(-225px);
    width: 450px;
    height: 490px;
  }
  .paragraph-container {
    /* display: flex; */
    width: 65vw;
    font-size: 8px;
    /* align-items: center; */
    text-align: center;
  }
}
</style>
