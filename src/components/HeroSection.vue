<script>
// export default {
//   name: "HeroSection",
// };
</script>
<template>
  <div class="hero-container">
    <h1>A modern publishing platform</h1>
    <p>Grow your audience and build your online brand</p>
    <div class="btn-container">
      <button class="btn-one">Start For Free</button>
      <button class="btn-two">Learn More</button>
    </div>
  </div>
</template>
<style scoped>
@import url("https://fonts.google.com/specimen/Overpass?preview.text_type=custom");
@import url("https://fonts.google.com/specimen/Ubuntu?preview.text_type=custom");
.hero-container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  height: 30rem;
}
h1,
p {
  color: white;
}
h1 {
  font-family: "Overpass", Arial, Helvetica, sans-serif, monospace;
  font-size: 4.6rem;
  font-weight: 300;
  margin-bottom: 1.5rem;
}
p {
  font-family: "Ubuntu", Arial, Helvetica, sans-serif, monospace;
  font-size: 1.8rem;
  margin-bottom: 3rem;
}
button {
  font-family: "Ubuntu", Arial, Helvetica, sans-serif, monospace;
  font-weight: 600;

  /* background-color: transparent; */
  cursor: pointer;
  padding: 1rem 1.5rem 1rem 1.5rem;

  border: none;
  border-radius: 20px;
  /* background-color: inherit; */
  border: solid white 1.5px;
}
.btn-container {
  width: 23.5rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.btn-one {
  color: hsl(356, 100%, 66%);
  background-color: white;
}
.btn-two {
  color: white;
  background-color: inherit;
}
/* .button:hover {
  background-color: white;
  color: inherit;
} */
</style>
