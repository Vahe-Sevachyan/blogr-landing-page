<script>
import NavBar from "./components/NavBar.vue";
import HeroSection from "./components/HeroSection.vue";
import BodyOne from "./components/BodyOne.vue";
import BodyTwo from "./components/BodyTwo.vue";
export default {
  name: "App",
  components: {
    NavBar,
    HeroSection,
    BodyOne,
    BodyTwo,
  },
};
</script>

<template>
  <div class="main-container">
    <div class="header">
      <NavBar />
      <HeroSection />
    </div>
    <body>
      <BodyOne />
      <BodyTwo />
    </body>
  </div>
</template>

<style scoped>
.header {
  background-color: hsl(356, 100%, 66%);
  background-image: url("./assets/images/bg-pattern-intro-desktop.svg");
  /* background-size: cover;
  background-position-x: center;
  background-position-y: center;
  -webkit-background-size: cover; */
  /* ******************************** */
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  background-position-x: center;
  background-position-y: center;
  /* max-width: 170rem; */
  width: 100%;
  margin: auto;
  height: 70vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
</style>
