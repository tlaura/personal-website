<template>
  <div class="main-container">
    <div class="portfolio-header">
      <h1>Portfolio</h1>
    </div>
    <div class="portfolio-container">
      <div class="portfolio-content portfolio-content-left">
        <div class="content-title">
          <div>
            <img src="../assets/marsproject.png" class="project-img" />
          </div>
          <div class="title">
            <h3>Mars Autism Institution</h3>
            <br />
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
        <div class="content-description">
          Built a web platform for a non-profit connecting children living with
          autism to support services.
          <br />
          <br />
          <br />
          <u>Technologies:</u>
          <br />
          <br />
          <p>
            <strong>
              Java (Spring), TypeScript (Angular), MySQL, JUnit/Mockito, Gilab
              CI/CD
            </strong>
          </p>
        </div>
      </div>
      <div class="portfolio-content portfolio-content-right">
        <div class="content-title">
          <div>
            <img src="../assets/codenames2.png" class="project-img" />
          </div>
          <div class="title">
            <h3>Codenames</h3>
            <br />
            <h5>
              <a
                href="https://github.com/CaIlbackCats/codenames"
                target="_blank"
                rel="noopener noreferrer"
                >github.com/CallbackCats/codenames</a
              >
            </h5>
          </div>
        </div>
        <div class="content-description">
          Built a multiplayer online game based on a boardgame in a Scrum team
          of 3 developers.
          <br />
          <br />
          <br />
          <u>Technologies:</u>
          <br />
          <br />
          <p>
            <strong>
              Java (Spring), TypeScript (VueJS), MySQL, JUnit, AWS (EC2), Github
              Actions
            </strong>
          </p>
        </div>
      </div>
    </div>
    <div class="portfolio-nav">
      <Nav color="#45b29a"></Nav>
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
h1 {
  padding-bottom: 60px;
}

p {
  text-indent: 50px;
}
h3 {
  font-weight: 700;
  font-size: 2rem;
}

h5 {
  font-style: italic;
}

.content-description {
  display: flex;
  text-align: left;
  flex-direction: column;
  padding: 1rem;
}

.title {
  padding-top: 2rem;
  display: flex;
  justify-content: center;
  flex-direction: column;
  width: 100%;
}

.project-img {
  height: 200px;
  width: 350px;
  border-radius: 2%;
}

.main-container {
  display: flex;
  flex-direction: column;
}

.portfolio-nav {
  display: block;
  padding-top: 150px;
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
  color: #45b29a;
  border-radius: 1%;
  font-size: 1.2rem;
}

.portfolio-content-left {
  margin-left: 8rem;
  margin-right: 5rem;
  margin-bottom: 2rem;
}

.portfolio-content-right {
  margin-left: 5rem;
  margin-right: 8rem;
  margin-bottom: 2rem;
}

.content-title {
  display: flex;
  flex-direction: row;
  padding: 1rem;
}
</style>
