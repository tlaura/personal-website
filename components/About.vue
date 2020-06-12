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
    <div class="half-container"></div>
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
}
.left-container {
  justify-content: space-between;
}
.green {
  background-color: #45b29a;
}
</style>
