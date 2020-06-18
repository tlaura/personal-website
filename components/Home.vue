<template>
  <div>
    <div class="social-container">
      <div class="social-logo linkedin">
        <fa :icon="faLinkedin" />
      </div>
      <div class="social-logo github">
        <fa :icon="faGithub" />
      </div>
    </div>
    <div class="home-container">
      <div class="text">
        <h1>Hi, I'm Laura,</h1>
        <h2>
          a Full-Stack Software Engineer.
        </h2>
      </div>
    </div>
    <div class="home-nav">
      <Nav color="#45b29a"></Nav>
    </div>
  </div>
</template>

<script>
import { faGithub } from '@fortawesome/free-brands-svg-icons'
import { faLinkedin } from '@fortawesome/free-brands-svg-icons'
import Nav from '~/components/Nav'

export default {
  components: {
    Nav
  },
  computed: {
    faLinkedin() {
      return faLinkedin
    },
    faGithub() {
      return faGithub
    }
  }
}
</script>
<style>
.home-nav {
  display: block;
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
}

h1 {
  font-weight: 700;
  font-size: 80px;
  margin-bottom: 10px;
  /* color: #45b29a; */
}

.home-container {
  height: 100%;
  display: flex;
  align-items: center;
}
.text {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  max-width: 650px;
  margin-bottom: 10vh;
}
.text > h4 {
  text-align: left;
}

.social-logo {
  z-index: 10;
}

.social-logo > svg {
  font-size: 3.5rem;
  cursor: pointer;
  margin-left: 1.5rem;
  transition: 1.5;
}

.social-logo > svg:hover {
  font-size: 3.8rem;
}

.social-logo {
  position: fixed;
  top: 1rem;
  display: flex;
}
.github {
  right: 1rem;
}
.linkedin {
  right: 6rem;
}
</style>
