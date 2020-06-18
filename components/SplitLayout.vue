<template>
  <div class="layout-container" :style="layoutDirection">
    <div class="half-container green left-container">
      <div class="header">
        <h1>{{ title }}</h1>
      </div>
      <div class="about-nav">
        <Nav color="#e0ebe8"></Nav>
      </div>
    </div>
    <div class="half-container">
      <slot></slot>
    </div>
  </div>
</template>

<script>
import Nav from '~/components/Nav'
export default {
  components: {
    Nav
  },
  props: {
    title: String,
    reverse: Boolean
  },
  computed: {
    layoutDirection() {
      return this.reverse
        ? { 'flex-direction': 'row-reverse' }
        : { 'flex-direction': 'row' }
    }
  }
}
</script>
<style scoped>
.layout-container {
  position: relative;
  display: flex;
  align-items: stretch;
  width: 100%;
}
.header {
  display: flex;
  flex-direction: column;
  justify-content: center;
  flex-grow: 1;
}
h1 {
  font-weight: 700;
  font-size: 80px;
  margin-bottom: 10px;
  color: #e0ebe8;
}

.half-container {
  width: 50%;
}
.left-container {
  justify-content: space-between;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.green {
  background-color: #45b29a;
}
</style>
