<template>
  <div>
    <div class="portfolio-header">
      <h1>Portfolio</h1>
    </div>
    <div class="portfolio-container">
      <div class="portfolio-content">
        First Project
      </div>
      <div class="portfolio-content">
        Second project
      </div>
    </div>
    <div class="portfolio-nav">
      <Nav color="#e0ebe8"></Nav>
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
.portfolio-nav {
  display: block;
  position: relative;
  left: 0;
  right: 0;
  bottom: 0;
  padding-top: 4rem;
}

h1 {
  font-weight: 700;
  font-size: 80px;
  margin-bottom: 10px;
}

.portfolio-header {
  padding-bottom: 4rem;
  padding-top: 3rem;
}

.portfolio-container {
  display: flex;
  margin: 0px auto;
  align-content: center;
  width: 100%;
}

.portfolio-content {
  display: inline-block;
  width: 370px;
  height: 370px;
  margin: 0 auto;
  /* padding-left: 5px;
  padding-right: 5px; */
}

@keyframes appear {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>
