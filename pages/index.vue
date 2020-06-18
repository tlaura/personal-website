<template>
  <div>
    <div class="container green">
      <Home></Home>
    </div>
    <div id="about" class="container white">
      <About></About>
    </div>
    <div id="portfolio" class="container green">
      <Portfolio></Portfolio>
    </div>
    <div id="contact" class="container green">
      <Contact></Contact>
    </div>
  </div>
</template>

<script>
import Home from '~/components/Home.vue'
import About from '~/components/About.vue'
import Portfolio from '~/components/Portfolio.vue'
import Contact from '~/components/Contact.vue'

export default {
  components: {
    Home,
    About,
    Portfolio,
    Contact
  }
}
</script>

<style scoped>
.container {
  height: 100vh;
  width: 100%;
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
