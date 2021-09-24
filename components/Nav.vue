<template>
  <div>
    <nav class="main-nav" :style="style">
      <ul>
        <li>
          <a href="#home">Home</a>
        </li>
        <li>
          <a href="#about">About</a>
        </li>
        <li>
          <a href="#contact">Contact</a>
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
ul {
  list-style: none;
  padding: 32px 0;
  text-align: center;
}
.main-nav ul li {
  display: inline;
  font-size: 16px;
}

.main-nav ul li:before {
  content: '/';
  padding: 0 10px 0 7px;
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
  border-bottom: 2px solid white;
}
</style>
