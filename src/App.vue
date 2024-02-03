<script>
import NavBar from "./components/NavBar.vue";
export default {
  name: "App",
  components: {
    NavBar,
  },
};
</script>

<template>
  <div class="main-container">
    <div class="header">
      <NavBar />
    </div>
  </div>
</template>

<style scoped>
.header {
  background-color: hsl(356, 100%, 66%);
  height: 20vh;
}
</style>
