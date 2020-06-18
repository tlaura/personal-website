<template>
  <SplitLayout title="Contact me">
    <div class="contact-container">
      <p>
        I'm available for full-time employment or if you want to collaborate,
        feel free to contact me.
      </p>
      <br />
      <br />
      <h3>Laura Tarczi</h3>
      <br />
      <a href="mailto:tarczi.laura.01@gmail.com">tarczi.laura.01@gmail.com</a>
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
  justify-content: center;
  padding: 0 100px;
  font-size: 1.2em;
  text-align: left;
  color: #545454;
}
</style>
