<template>
  <div class="main-container">
    <div class="portfolio-header">
      <h1>Portfolio</h1>
    </div>
    <div class="portfolio-container">
      <div class="portfolio-content">
        <div class="content-title">
          <div>
            <img src="../assets/marsproject.png" class="project-img" />
          </div>
          <div class="title">
            <h3>Mars Autism Foundation</h3>

            <h5>
              <a
                href="https://github.com/tlaura/mars"
                target="_blank"
                rel="noopener noreferrer"
                >github.com/tlaura/mars</a
              >
            </h5>
          </div>
        </div>

        <div>
          dfabkwelfndksfsadfln Having graduated from the University of
          Birmingham, I then worked in client facing roles in finance and
          consulting out of New York.
        </div>
      </div>
      <div class="portfolio-content">
        <div>
          <div class="content-title">
            <img src="../assets/codenames2.png" class="project-img" />
          </div>
        </div>
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
h3 {
  font-weight: 700;
}

h5 {
  font-style: italic;
}

.title {
  padding-top: 2rem;
  display: flex;
  justify-content: center;
  flex-direction: column;
  width: 100%;
}

.project-img {
  height: 250px;
  width: 400px;
  border-radius: 2%;
}
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
  margin: 1.5%;
  border-radius: 1%;
}

.content-title {
  display: flex;
  flex-direction: row;
  padding: 1rem;
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
