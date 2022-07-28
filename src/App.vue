<template>
  <div>
      <TheHeader />

      <div class="jumbotron"></div>

      <TheMain :series-list="seriesList"/>

      <TheBanner />

      <TheFooter />
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import TheMain from './components/TheMain.vue'
import TheFooter from './components/TheFooter.vue'
import TheBanner from './components/TheBanner.vue'
import seriesList from './dc-comics.json';

export default {
  name: 'App',
  components: {
    TheHeader,
    TheMain,
    TheBanner,
    TheFooter
  },

  props: {
  },

  data() {
    return {
      seriesList,
    }
  }
}
</script>

<style lang="scss">
@import "./assets/sass/style.scss";

.jumbotron {
  height: 250px;
  background-image: url(./assets/img/jumbotron.jpg);
  background-repeat: no-repeat;
  // background-position:;
  background-size: cover;
}
</style>
