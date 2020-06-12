<template>
  <div class="about-container">
    <div class="half-container green">
      <h1>About.</h1>
      <div class="about-nav">
        <Nav color="#e0ebe8"></Nav>
      </div>
    </div>
    <div class="half-container">
      <h1>About2</h1>
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
.about-nav {
  display: block;
  position: absolute;
  bottom: 0;
  left: 15%;
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
}
.green {
  background-color: #45b29a;
}
</style>
