<template>
  <div class="main-container">
    <div class="portfolio-header">
      <h1>Portfolio</h1>
    </div>
    <div class="portfolio-container">
      <div class="portfolio-content">
        First Project
        <div>
          adlihfawfdjkns
        </div>
        <div>
          dfabkwelfndksfsadfln Having graduated from the University of
          Birmingham, I then worked in client facing roles in finance and
          consulting out of New York.
        </div>
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
.main-container {
  display: flex;
  flex-direction: column;
  width: 98%;
}

.portfolio-nav {
  display: block;
  position: relative;
  left: 0;
  right: 0;
  bottom: 0;
}

h1 {
  font-weight: 700;
  font-size: 80px;
  margin-bottom: 10px;
}

.portfolio-header {
  padding-bottom: 2rem;
  padding-top: 3rem;
}

.portfolio-container {
  display: flex;
  flex-direction: row;
  justify-content: center;
  flex-grow: 1;
}

.portfolio-content {
  background-color: white;
  width: 100%;
  display: flex;
  flex-direction: column;
  color: #545454;
  margin: 1%;
  border-radius: 2%;
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
