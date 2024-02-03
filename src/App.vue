<script>
import NavBar from "./components/NavBar.vue";
import HeroSection from "./components/HeroSection.vue";
export default {
  name: "App",
  components: {
    NavBar,
    HeroSection,
  },
};
</script>

<template>
  <div class="main-container">
    <div class="header">
      <NavBar />
      <HeroSection />
    </div>
  </div>
</template>

<style scoped>
.header {
  background-color: hsl(356, 100%, 66%);
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
