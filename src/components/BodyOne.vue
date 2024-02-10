<script>
// export default {
//   name: "BodyOne",
// };
</script>

<template>
  <div class="body-one-container">
    <h2>Designed for the future</h2>
    <div class="body-one-display">
      <div class="description-paragraph">
        <h3>Introducing an extensible editor</h3>
        <p>
          blogr teatures an exceedingly inturive interrace wnich lets you tocus
          on one thing: creating content. The editor supports management of
          multiple blogs and allows easy manipulation of embeds such as images,
          videos, and Markdown. Extensibility with plugins and themes provide
          easy ways to add functionality or change the looks of a blog
        </p>
        <h3>Robust content management</h3>
        <p>
          Flexible content management enables users to easily move through
          posts. Increase the usability of your blog by adding customized
          categories, sections, format, or flow. With this functionality, you're
          in full control.
        </p>
      </div>
      <img src="../assets/images/illustration-editor-desktop.svg" alt="" />
    </div>
  </div>
</template>

<style scoped>
@import url("https://fonts.google.com/specimen/Overpass?preview.text_type=custom");
@import url("https://fonts.google.com/specimen/Ubuntu?preview.text_type=custom");

.body-one-container {
  width: 85%;
  /* height: 60rem; */
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-top: 2rem;
  margin-bottom: 5rem;
}
h2 {
  font-size: 3.5rem;
  margin: 3rem 0 3rem 0;
  font-family: "Ubuntu", Arial, Helvetica, sans-serif, monospace;
  color: hsl(208, 46%, 35%);
}

h3 {
  color: hsl(208, 46%, 35%);
  font-size: 3rem;
  font-weight: 500;
}
.body-one-display {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 60rem;
}
.description-paragraph {
  display: flex;
  flex-direction: column;
  width: 80rem;
  font-size: 1.8rem;
}
p {
  margin-bottom: 2rem;
  color: hsl(208, 46%, 35%);
  font-size: 1.7rem;
}
.description-paragraph h3 {
  margin-bottom: 2.5rem;
}
img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

@media only screen and (max-width: 1250px) {
  .body-one-container {
    margin-top: 1rem;
    margin-bottom: 2rem;
  }
  img {
    max-width: 70%;
    max-height: 70%;
  }
  h2 {
    font-size: 2.5rem;
    margin: 2rem 0 0rem 0;
  }
  h3 {
    font-size: 2.5rem;
  }
  p {
    font-size: 1.2rem;
  }
}
@media only screen and (max-width: 875px) {
  .body-one-display {
    flex-direction: column-reverse;
    margin-bottom: 10rem;
  }
  h2 {
    margin-bottom: 7rem;
  }
  .description-paragraph {
    width: 50rem;
  }
  img {
    margin-bottom: 4rem;
  }
}
</style>
