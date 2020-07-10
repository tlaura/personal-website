<template>
  <div>
    <div class="social-logo linkedin">
      <a href="https://www.linkedin.com/in/laura-tarczi/" target="_blank">
        <fa :icon="faLinkedin"> </fa>
      </a>
    </div>

    <div class="social-logo github">
      <a href="https://github.com/tlaura" target="_blank">
        <fa :icon="faGithub"></fa
      ></a>
    </div>
  </div>
</template>

<script>
import { faGithub, faLinkedin } from '@fortawesome/free-brands-svg-icons'

export default {
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

<style scoped>
a,
a:visited {
  color: #45b29a;
}

.social-logo {
  font-size: 2.8rem;
  cursor: pointer;
  margin-left: 1rem;
  transition: 1.5;
}

.social-logo:hover {
  font-size: 3.1rem;
}

.social-logo {
  position: absolute;
  top: 1rem;
  display: flex;
}

.github {
  right: 1rem;
}
.linkedin {
  right: 5rem;
}
</style>
