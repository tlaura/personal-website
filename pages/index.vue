<template>
  <div>
    <div class="container green">
      <Home></Home>
    </div>
    <div id="about" class="container white">
      <About></About>
    </div>
  </div>
</template>

<script>
import Home from '~/components/Home.vue'
import About from '~/components/About.vue'

export default {
  components: {
    Home,
    About
  }
}
</script>

<style scoped>
.container {
  margin: 0 auto;
  min-height: 100vh;
  min-width: 100vw;
  display: flex;
  justify-content: center;
  align-items: stretch;
  text-align: center;
  padding: 0;
}
.green {
  background-color: #e0ebe8;
}
.white {
  /* background: linear-gradient(
    to right,
    #45b29a 0%,
    #45b29a 50%,
    #ffffff 50%,
    #ffffff 100%
  ); */
  background-color: #ffffff;
}
</style>
