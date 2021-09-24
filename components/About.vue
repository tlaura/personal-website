<template>
  <SplitLayout title="About me" reverse>
    <div class="description-container">
      <img src="../assets/lt3.jpg" class="rounded-img" />
      <div class="about-description">
        I’m a software engineer based in London, looking to progress in a
        fast-moving, collaborative environment.
        <br /><br />
        Having graduated from the University of Birmingham, I then worked in
        client facing roles in finance and consulting out of New York.
        <br /><br />
        In 2019, I made the decision to move into technology and have since
        gained experience as a full-stack developer at a fintech trading firm
        and currently at a global software consultancy.
        <br /><br />
        My key skills:
        <br />
        <ul>
          <li>Infrastructure: <strong>AWS, Azure</strong></li>
          <li>Backend: <strong>Python, Java</strong></li>
          <li>Frontend: <strong>React, VueJS</strong></li>
        </ul>
      </div>
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
