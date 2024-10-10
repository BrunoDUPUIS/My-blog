<template>
  <footer>
    <p>
      Made with <a href="https://vuejs.org/" target="_blank">Vue.js</a> by
      <a href="https://github.com/BrunoDUPUIS/BrunoDUPUIS" target="_blank">Bruno DUPUIS</a>
    </p>
  </footer>
</template>
<style scoped>
footer {
  /* border: 3px solid green; */
  display: flex;
  justify-content: center;
  align-items: center;
  height: var(--footer-heigth);
}
span {
  color: var(--main-orange);
  font-weight: bold;
}
a {
  text-decoration: none;
  color: var(--main-orange);
  font-weight: bold;
  cursor: pointer;
}
</style>
