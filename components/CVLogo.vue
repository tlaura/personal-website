<template>
  <div>
    <a
      href="https://drive.google.com/file/d/1geeZ1kDWuuvznfhfBEihvKK5jrXU1W9v/view?usp=sharing"
      target="_blank"
    >
      <div class="cv-link">
        CV
      </div>
    </a>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.cv-link {
  font-size: 1.5rem;
  font-weight: 700;
  border-radius: 50%;
  color: #e0ebe8;
  line-height: 3rem;
  text-align: center;
  background-color: #45b29a;
  width: 3rem;
  height: 3rem;
  transition: 1.5;
  position: absolute;
}

.cv-link:hover {
  font-size: 1.6rem;
  line-height: 3.2rem;
  width: 3.2rem;
  height: 3.2rem;
}

a,
a:visited {
  color: #45b29a;
}
</style>
