<script>
import NavBar from "./components/NavBar.vue";
import HeroSection from "./components/HeroSection.vue";
import BodyOne from "./components/BodyOne.vue";
import BodyTwo from "./components/BodyTwo.vue";
import BodyThree from "./components/BodyThree.vue";
import FooterSection from "./components/FooterSection.vue";
export default {
  name: "App",
  components: {
    NavBar,
    HeroSection,
    BodyOne,
    BodyTwo,
    BodyThree,
    FooterSection,
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
      <BodyThree />
      <FooterSection />
    </body>
  </div>
</template>

<style scoped>
.header {
  background-color: hsl(356, 100%, 66%);
  background-image: url("./assets/images/bg-pattern-intro-desktop.svg");
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  background-position-x: center;
  background-position-y: center;
  width: 100%;
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  border-bottom-left-radius: 90px;
}
</style>
