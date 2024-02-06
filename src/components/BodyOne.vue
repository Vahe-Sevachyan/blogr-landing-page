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
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eum iste
          autem, enim quibusdam impedit recusandae consequatur minima reiciendis
          ipsam voluptatum exercitationem laboriosam quo natus. Recusandae dolor
          ad deleniti blanditiis velit.
        </p>
        <h3>Robust content management</h3>
        <p>
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
h2 {
  font-size: 3rem;
  margin-bottom: 3rem;
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
  width: 40vw;
  font-size: 1.8rem;
}
.description-paragraph p {
  color: #2c2d3f;
  margin-bottom: 2rem;
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
