<script>
export default {
  props: {
    comics: Array
  },
  data() {
    return {}
  }
}
</script>

<template>
  <div class="card-container">
    <div class="card" v-for="comic in comics" :key="comic.series">
      <figure>
        <img :src="comic.thumb" :alt="comic.series">
      </figure>
      <div>{{ comic.series }}</div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.card-container {
  display: flex;
  flex-wrap: wrap;
  margin: 50px;
  height: 400px;
  width: 90%;
}

.card {
  flex-basis: calc(100% / 6);
  height: 100px;
  padding: 10px;
}

figure {
  height: 160px;
  width: auto;
  margin: 10px 0 10px;
}

img {
  object-fit: cover;
  display: block;
  height: 100%;
  width: 100%;
  object-position: 0 0;
}
</style>