<template>
  <SplitLayout title="Contact me">
    <div class="contact-container">
      <p>
        I'm currently available for full-time employment.
      </p>
      <br />
      <br />
      <h3>Laura Tarczi</h3>
      <br />
      <a href="mailto:tarczi.laura.01@gmail.com">tarczi.laura.01@gmail.com</a>
      <br />
      <br />
      <div class="contact-links">
        <div class="cv-logo">
          <CVLogo></CVLogo>
        </div>
        <div class="social-logo linkedin">
          <fa :icon="faLinkedin" />
        </div>
        <div class="social-logo github">
          <fa :icon="faGithub" />
        </div>
      </div>
    </div>
  </SplitLayout>
</template>

<script>
import { faGithub } from '@fortawesome/free-brands-svg-icons'
import { faLinkedin } from '@fortawesome/free-brands-svg-icons'
import SplitLayout from '~/components/SplitLayout'
import CVLogo from '~/components/CVLogo'

export default {
  components: {
    SplitLayout,
    CVLogo
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
<style scoped>
h1 {
  color: #545454;
}

a,
a:visited {
  color: #45b29a;
}
.contact-container {
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: start;
  padding: 250px 100px;
  font-size: 1.4em;
  text-align: left;
  color: #545454;
}
.contact-links {
  display: flex;
}

.social-logo > svg {
  font-size: 3.7rem;
  cursor: pointer;
  margin-left: 1.5rem;
  transition: 1.5;
  color: #45b29a;
}

.social-logo > svg:hover {
  font-size: 3.8rem;
}

.github {
  position: absolute;
  padding-left: 8.7rem;
}

.linkedin {
  position: absolute;
  padding-left: 3.7rem;
  z-index: 10;
}

.cv-logo {
  z-index: 11;
}
</style>
