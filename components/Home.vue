<template>
  <div>
    <div class="social-container">
      <SocialLogo></SocialLogo>
    </div>
    <div class="home-container">
      <div class="text">
        <h1>Hi, I'm Laura,</h1>
        <h3>
          a Full-Stack Software Engineer.
        </h3>
      </div>
    </div>
    <div class="home-nav">
      <Nav color="#45b29a"></Nav>
    </div>
  </div>
</template>

<script>
import Nav from '~/components/Nav'
import SocialLogo from '~/components/SocialLogo'

export default {
  components: {
    Nav,
    SocialLogo
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
  font-size: 65px;
  margin-bottom: 7px;
  /* color: #45b29a; */
}

h3 {
  font-size: 20px;
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
  max-width: 550px;
  margin-bottom: 10vh;
}
.text > h4 {
  text-align: left;
}

.social-container {
  z-index: 10;
}
</style>
