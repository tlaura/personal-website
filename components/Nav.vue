<template>
  <div>
    <nav class="main-nav" :style="style">
      <ul>
        <li>
          <a href="#about">About</a>
        </li>
        <li>
          <a href="#">Portfolio</a>
        </li>
        <li>
          <a href="#">Contact</a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  props: ['color'],
  computed: {
    style() {
      return { color: this.color }
    }
  }
}
</script>

<style scoped>
/* .main-nav {
  display: block;
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
} */
ul {
  list-style: none;
  padding: 36px 0;
  text-align: center;
}
.main-nav ul li {
  display: inline;
  font-size: 20px;
}

.main-nav ul li:before {
  content: '/';
  padding: 0 12px 0 9px;
}

.main-nav ul li:first-child:before {
  display: none;
}

.main-nav ul li a {
  color: inherit;
  text-decoration: none;
  text-transform: uppercase;
  cursor: pointer;
}

.main-nav ul li a:hover {
  padding-bottom: 0.5rem;
  border-bottom: 3px solid white;
}
</style>
