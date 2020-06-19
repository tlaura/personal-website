<template>
  <div>
    <a href="#" target="_blank">
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
  line-height: 3.5rem;
  text-align: center;
  background-color: #45b29a;
  width: 3.5rem;
  height: 3.5rem;
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
