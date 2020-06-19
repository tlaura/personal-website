<template>
  <div>
    <div class="social-logo linkedin">
      <fa :icon="faLinkedin" />
    </div>
    <div class="social-logo github">
      <fa :icon="faGithub" />
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
