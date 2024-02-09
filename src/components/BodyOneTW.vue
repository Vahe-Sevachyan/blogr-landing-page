<script>
// export default {
//   name: "BodyOne",
// };
</script>

<template>
  <div class="container px-4 mx-auto sm:px-6 lg:px-8">
    <h2 class="mb-8 text-3xl font-bold text-center md:text-4xl lg:text-5xl">
      Designed for the future
    </h2>
    <div
      class="flex flex-col-reverse items-center justify-center gap-8 md:flex-row"
    >
      <div class="md:w-1/2">
        <div>
          <h3 class="mb-4 text-xl font-bold md:text-2xl">
            Introducing an extensible editor
          </h3>
          <p class="mb-4">
            blogr features an exceedingly intuitive interface which lets you
            focus on one thing: creating content. The editor supports management
            of multiple blogs and allows easy manipulation of embeds such as
            images, videos, and Markdown. Extensibility with plugins and themes
            provide easy ways to add functionality or change the looks of a
            blog.
          </p>
          <h3 class="mb-4 text-xl font-bold md:text-2xl">
            Robust content management
          </h3>
          <p class="mb-4">
            Flexible content management enables users to easily move through
            posts. Increase the usability of your blog by adding customized
            categories, sections, format, or flow. With this functionality,
            you're in full control.
          </p>
        </div>
      </div>
      <div class="md:w-1/2">
        <img
          src="../assets/images/illustration-editor-desktop.svg"
          alt=""
          class="w-full"
        />
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url("https://fonts.google.com/specimen/Overpass?preview.text_type=custom");
@import url("https://fonts.google.com/specimen/Ubuntu?preview.text_type=custom");
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
.description-img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}
</style>
