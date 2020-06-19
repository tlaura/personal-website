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
  font-size: 1.8rem;
  font-weight: 700;
  border-radius: 50%;
  color: #e0ebe8;
  line-height: 3.6rem;
  text-align: center;
  background-color: #45b29a;
  width: 3.6rem;
  height: 3.6rem;
  transition: 1.5;
  position: absolute;
}

.cv-link:hover {
  font-size: 1.9rem;
  line-height: 3.7rem;
  width: 3.7rem;
  height: 3.7rem;
}

a,
a:visited {
  color: #45b29a;
}
</style>
