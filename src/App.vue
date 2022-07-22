<template>
  <div>
      <TheHeader />

      <main>

      </main>

      <footer>

      </footer>

  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'

export default {
  name: 'App',
  components: {
    TheHeader,
  }
}
</script>

<style lang="scss">
// reset
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  height: 100vh;  
  font-family: "Segoe UI", "Open Sans", Helvetica, sans-serif;
}

img {
  max-width: 100%;
  height: auto;
}

ul {
  list-style-type: none;
}

a {
  text-decoration: none;
}

// utils
.container {
  max-width: 1200px;
  height: 100%;
  margin: 0 auto;
  text-align: center;
}
</style>
