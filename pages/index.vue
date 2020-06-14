<template>
  <div>
    <div class="container green">
      <Home></Home>
    </div>
    <div id="about" class="container white">
      <About></About>
    </div>
    <div id="portfolio" class="container dark-green">
      <Portfolio></Portfolio>
    </div>
  </div>
</template>

<script>
import Home from '~/components/Home.vue'
import About from '~/components/About.vue'
import Portfolio from '~/components/Portfolio.vue'

export default {
  components: {
    Home,
    About,
    Portfolio
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
.dark-green {
  background-color: #45b29a;
  color: #e0ebe8;
}
.green {
  background-color: #e0ebe8;
}
.white {
  background-color: #ffffff;
}
</style>
