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
        <p class="description-paragraph">
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eum iste
          autem, enim quibusdam impedit recusandae consequatur minima reiciendis
          ipsam voluptatum exercitationem laboriosam quo natus. Recusandae dolor
          ad deleniti blanditiis velit.
        </p>
        <h3>Robust content management</h3>
        <p class="description-paragraph">
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eum iste
          autem, enim quibusdam impedit recusandae consequatur minima reiciendis
          ipsam voluptatum exercitationem laboriosam quo natus. Recusandae dolor
          ad deleniti blanditiis velit.
        </p>
      </div>
      <img
        class="description-img"
        src="../assets/images/illustration-editor-desktop.svg"
        alt=""
      />
    </div>
  </div>
</template>

<style scoped>
.body-one-container {
  width: 85%;
  /* height: 60rem; */
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-top: 2rem;
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
  max-width: 100%;
  max-height: 100%;
}
.description-paragraph {
  font-size: 1.3vw;
}
.description-img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}
</style>
