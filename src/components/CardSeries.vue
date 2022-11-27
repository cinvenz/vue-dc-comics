<template>
  <div class="card">
    <div class="contents">
      <img class="img-card" :src="imgUrl" alt="" />
      <p class="card-name">{{ name }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "CardSeries",
  props: {
    imgUrl: String,
    name: String,
  },
};
</script>

<style lang="scss" scoped>
.card {
  margin-top: 2rem;
  .contents {
    width: 8rem;
    img {
      width: 8rem;
      height: 8rem;
      object-fit: cover;
      object-position: top;
      cursor: pointer;
    }
    .card-name {
      font-size: 0.5em;
      color: white;
      padding-top: 0.5rem;
      cursor: pointer;
      &:hover {
        color: red;
      }
    }
  }
}
</style>
