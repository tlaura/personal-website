<template>
  <div>
    <h1>Hi, I'm Laura.</h1>
    <nav class="main-nav">
      <ul>
        <li>
          <a class="underlined-white" href="#">About</a>
        </li>
        <li>
          <a class="underlined-white" href="#">Portfolio</a>
        </li>
        <li>
          <a class="underlined-white" href="#">Contact</a>
        </li>
      </ul>
    </nav>
  </div>
</template>
<style>
h1 {
  font-weight: 700;
  font-size: 80px;
  margin-bottom: 50px;
  /* color: #45b29a; */
}
.main-nav {
  display: block;
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
}
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

@keyframes appear {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>
