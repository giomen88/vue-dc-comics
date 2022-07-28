<template>
  <main>
    <div id="content">
      <div class="container">
        <div v-for="serie in seriesList" :key="serie.series" class="card">
          <a href="">
            <img :src="serie.thumb" :alt="serie.series" />
            <h1>{{ serie.series }}</h1>
          </a>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "TheMain",
  props: {
    seriesList: Array,
  },
};
</script>

<style lang="scss" scoped>
main {
  background-color: #000000;
  color: #fcfcfc;
  padding: 30px 0;

  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;

    .card {
      flex-basis: calc(100% / 6);
      margin-bottom: 10px;
      text-align: center;

      img {
        width: 100px;
        height: 100px;
        object-fit: cover;
        object-position: top;
        margin-bottom: 5px;
      }

      a {
        color: #fcfcfc;
        font-size: 0.3rem;
      }
    }
  }
}
</style>