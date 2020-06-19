<template>
  <SplitLayout title="Contact me">
    <div class="contact-container">
      <p>
        I'm currently available for full-time employment.
      </p>
      <p>
        If you'd like to connect, feel free to get in touch.
      </p>
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
          <a href="https://www.linkedin.com/in/laura-tarczi/" target="_blank">
            <fa :icon="faLinkedin"></fa>
          </a>
        </div>
        <div class="social-logo github">
          <a href="https://github.com/tlaura" target="_blank">
            <fa :icon="faGithub"></fa>
          </a>
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

p {
  margin-bottom: 20px;
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
  padding: 250px 80px;
  font-size: 1em;
  text-align: left;
  color: #545454;
}

.contact-links {
  display: flex;
}

.social-logo {
  font-size: 3.1rem;
  cursor: pointer;
  margin-left: 1rem;
  transition: 1.5;
  color: #45b29a;
}

.social-logo:hover {
  font-size: 3.2rem;
}

.github {
  position: absolute;
  padding-left: 7.8rem;
}

.linkedin {
  position: absolute;
  padding-left: 3.5rem;
  z-index: 10;
}

.cv-logo {
  z-index: 11;
  margin-top: 2px;
}
</style>
