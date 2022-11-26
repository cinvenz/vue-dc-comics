<template>
  <div class="card">
    <img
      class="img-card"
      src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
      alt=""
    />
    <p class="card-name">ACTION COMICS</p>
  </div>
</template>

<script>
export default {
  name: "CardSeries",
};
</script>

<style lang="scss" scoped>
.card {
  margin-top: 2rem;
  img {
    width: 8rem;
  }
  .card-name {
    font-size: 0.5em;
    color: white;
  }
}
</style>
