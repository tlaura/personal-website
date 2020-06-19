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
import { faGithub } from '@fortawesome/free-brands-svg-icons'
import { faLinkedin } from '@fortawesome/free-brands-svg-icons'

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
  font-size: 3.5rem;
  cursor: pointer;
  margin-left: 1.5rem;
  transition: 1.5;
}

.social-logo:hover {
  font-size: 3.8rem;
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
  right: 6rem;
}
</style>
