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
          <u>Technologies:</u>
          <br />
          <p>
            <strong>
              Java (Spring), TypeScript (Angular), MySQL, JUnit/Mockito, Gitlab
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
                href="https://github.com/CallbackCats/codenames"
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
          <u>Technologies:</u>
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
  font-weight: 700;
  font-size: 65px;
  margin-bottom: 70px;
}

p {
  text-indent: 20px;
}

h3 {
  font-weight: 700;
  font-size: 1.4rem;
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
  padding-top: 1rem;
  display: flex;
  justify-content: center;
  flex-direction: column;
  width: 100%;
}

.project-img {
  height: 150px;
  width: 250px;
  border-radius: 2%;
}

.main-container {
  display: flex;
  flex-direction: column;
}

.portfolio-nav {
  display: block;
  padding-top: 1.5rem;
  position: relative;
  left: 0;
  right: 0;
  bottom: 0;
}

.portfolio-header {
  padding-bottom: 1rem;
  padding-top: 2rem;
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
  font-size: 0.95rem;
}

.portfolio-content-left {
  margin-left: 8rem;
  margin-right: 4rem;
  margin-bottom: 4rem;
}

.portfolio-content-right {
  margin-left: 4rem;
  margin-right: 8rem;
  margin-bottom: 4rem;
}

.content-title {
  display: flex;
  flex-direction: row;
  padding: 1rem;
}
</style>
