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
        <div class="content-description">
          Consulted with a non-profit to build a web platform connecting
          children living with autism to support services during my time at
          Progmasters. Built using a RESTful Java Spring backend and an Angular
          9 / TypeScript frontend.
          <br />
          <br />
          <ul>
            <li>
              Collaborated with a 6-person Scrum team incl. 3 developers and the
              client’s product owner
            </li>
            <li>
              Implemented role-based authentication with JWT and configured CORS
              policies
            </li>
            <li>
              Automated deployment by setting up CI/CD pipeline in Gitlab
            </li>
            <li>
              Reduced text-search time from minutes to seconds using concurrency
              (Futures)
            </li>
            <li>Achieved 75% JUnit test coverage using TDD</li>
            <li>Integrated Google Maps and Google analytics APIs</li>
            <li>
              Managed code versioning using Git feature branches and pull
              requests
            </li>
          </ul>
        </div>
      </div>
      <div class="portfolio-content portfolio-content-right">
        <div>
          <div class="content-title">
            <img src="../assets/codenames2.png" class="project-img" />
          </div>
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
h3 {
  font-weight: 700;
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
  height: 250px;
  width: 400px;
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
  color: #545454;
  border-radius: 1%;
}
.portfolio-content-left {
  margin-left: 2rem;
  margin-right: 1rem;
}
.portfolio-content-right {
  margin-left: 1rem;
  margin-right: 2rem;
}

.content-title {
  display: flex;
  flex-direction: row;
  padding: 1rem;
}
</style>
