<template>
  <div class="card">
    <img
      :src="comics.thumb"
      :alt="comics.series"
    >
    <div class="comicsText">{{ comics.series }}</div>
  </div>
</template>

<script>
export default {
  props: {
    comics: Object,
  },
};
</script>

<style lang="scss" scoped>
  .card{
    text-align: center;
      width: 210px;
      height: 210px;
    img{
      width: 90%;
      height: 90%;
    }
  }

</style>
