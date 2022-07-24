<template>
  <div>
      <TheHeader />

      <TheMain />

      <TheBanner />

      <TheFooter />
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import TheMain from './components/TheMain.vue'
import TheFooter from './components/TheFooter.vue'
import TheBanner from './components/TheBanner.vue'

export default {
  name: 'App',
  components: {
    TheHeader,
    TheMain,
    TheBanner,
    TheFooter
  }
}
</script>

<style lang="scss">
@import "./assets/sass/style.scss";
</style>
