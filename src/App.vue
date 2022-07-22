<template>
  <div id="home">
      <TheHeader />

      <TheContent />

      <TheFooter />
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import TheContent from './components/TheContent.vue'
import TheFooter from './components/TheFooter.vue'

export default {
  name: 'App',
  components: {
    TheHeader,
    TheContent,
    TheFooter
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
  font-family: "Segoe UI", "Open Sans", Helvetica, sans-serif;
}

#home {
  height: 100vh; 
  display: flex;
  flex-direction: column;
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
}
</style>
