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
        I’m a software engineer based in London, and I'm looking to pursue a
        career in full-stack development.
        <br /><br />
        Having graduated from the University of Birmingham, I then worked in
        client facing roles in finance and consulting out of New York.
        <br /><br />
        In 2019, I made the decision to move into technology and have now
        completed an advanced coding bootcamp (Progmasters). I have deep
        experience in
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
  height: 300px;
  width: 300px;
  border-radius: 12%;
  display: inline-block;
  margin-bottom: 80px;
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
  /* background-color: #e0ebe8; */
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
  color: #545454;
}
</style>
