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
      <a href="#" target="_blank">
        <div class="cv-link">
          CV
        </div>
      </a>
    </div>
  </SplitLayout>
</template>

<script>
import SplitLayout from '~/components/SplitLayout'

export default {
  components: {
    SplitLayout
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

.cv-link {
  font-size: 2rem;
  font-weight: 700;
  border-radius: 50%;
  color: #e0ebe8;
  line-height: 3.8rem;
  text-align: center;
  background-color: #45b29a;
  width: 3.8rem;
  height: 3.8rem;
}
</style>
