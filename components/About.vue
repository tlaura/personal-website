<template>
  <SplitLayout title="About me" reverse>
    <div class="description-container">
      <img src="../assets/lt3.jpg" class="rounded-img" />
      <p class="about-description">
        I’m a software engineer based in London, looking to pursue a career in
        full-stack development.
        <br /><br />
        Having graduated from the University of Birmingham, I then worked in
        client facing roles in finance and consulting out of New York.
        <br /><br />
        In 2019, I made the decision to move into technology and have now
        completed an advanced coding bootcamp (Progmasters). I have experience
        in
        <strong>Python, Java Spring, VueJS </strong> and
        <strong>Angular</strong>.
      </p>
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
.rounded-img {
  height: 195px;
  width: 240px;
  border-radius: 8%;
  margin-bottom: 60px;
}

.description-container {
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 0 155px;
}

.about-description {
  font-size: 1em;
  text-align: left;
  color: #545454;
}
</style>
