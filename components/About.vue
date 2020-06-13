<template>
  <div class="about-container">
    <div class="half-container green left-container">
      <div class="header">
        <h1>About me</h1>
      </div>
      <div class="about-nav">
        <Nav color="#e0ebe8"></Nav>
      </div>
    </div>
    <div class="half-container description-container">
      <img src="../assets/laura_ca2.png" class="rounded-img" />
      <p class="about-description">
        I’m a software engineer, currently based in London, looking to pursue a
        career in full-stack development, to further develop my capabilities in
        the latest web and mobile technologies.
        <br /><br />
        After graduating from the University of Birmingham, I worked in finance
        and consulting in international businesses based out of New York. Having
        progressed quickly, I made the decision to leave the world of finance
        and make a career change into the multifaceted environment of
        technology.
        <br /><br />
        I recently completed an advanced coding bootcamp (Progmasters), where I
        thrived under the pressure of constantly learning new technologies and
        solving complex problems.
        <br /><br />
        My main technologies are
        <strong>Python, Java Spring, VueJS </strong> and
        <strong>Angular</strong>.
      </p>
    </div>
  </div>
</template>

<script>
import Nav from '~/components/Nav'
export default {
  components: {
    Nav
  }
}
</script>
<style scoped>
.rounded-img {
  height: 250px;
  width: 250px;
  border-radius: 12%;
  display: inline-block;
  margin-bottom: 40px;
}

.header {
  display: flex;
  flex-direction: column;
  justify-content: center;
  flex-grow: 1;
}
h1 {
  font-weight: 700;
  font-size: 80px;
  margin-bottom: 10px;
  color: #e0ebe8;
}
.about-container {
  position: relative;
  display: flex;
  flex-direction: row;
  align-items: stretch;
  width: 100%;
}
.half-container {
  width: 50%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.left-container {
  justify-content: space-between;
}
.green {
  background-color: #45b29a;
}
.description-container {
  padding: 0 200px;
}
.about-description {
  font-size: 1.2em;
  text-align: left;
  display: inline;
}
</style>
