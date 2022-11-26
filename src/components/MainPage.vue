<template>
  <main>
    <div class="container-black">
      <div class="main-img"></div>
      <div class="main-back">
        <div class="current-series">
          <p>CURRENT SERIES</p>
        </div>
        <div class="container cartoon-card">
          <CardSeries class="" v-for="i in 12" :key="i" />
        </div>
        <div class="">
          <button class="load-more">LOAD MORE</button>
        </div>
      </div>
    </div>
    <div class="container-blue-icon">
      <div class="container icons">
        <div class="icon">
          <img src="../../public/buy-comics-digital-comics.png" alt="" />
          <span>DIGITAL COMICS</span>
        </div>
        <div class="icon">
          <img src="../../public/buy-comics-merchandise.png" alt="" />
          <span>DC MERCHANDISE</span>
        </div>
        <div class="icon">
          <img src="../../public/buy-comics-subscriptions.png" alt="" />
          <span>SUBSCRIPTION</span>
        </div>
        <div class="icon">
          <img src="../../public/buy-comics-shop-locator.png" alt="" />
          <span>COMIC SHOP LOCATOR</span>
        </div>
        <div class="icon">
          <img src="../../public/buy-dc-power-visa.svg" alt="" />
          <span>DC POWER VISA</span>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
import CardSeries from "@/components/CardSeries.vue";

export default {
  name: "MainPage",
  components: {
    CardSeries,
  },
};
</script>

<style lang="scss" scoped>
main {
  .container-black {
    background-color: black;
    font-size: 1.5rem;
    .main-img {
      background-image: url(../../public/jumbotron.jpg);
      background-size: cover;
      background-repeat: no-repeat;
      height: 17rem;
    }
  }
  .current-series {
    background-color: #0282f9;
    height: 3rem;
    position: absolute;
    top: -1.5rem;
    left: 17.5%;
    color: white;
    font-size: 1.3rem;
    padding: 1rem 2rem;
    display: flex;
    align-items: center;
  }
  .main-back {
    background-color: #1c1c1c;
    position: relative;
    padding-bottom: 2rem;
  }
  .load-more {
    background-color: #0282f9;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: auto;
    color: white;
    border: none;
    padding: 0.5rem 2rem;
    cursor: pointer;
  }
  .cartoon-card {
    flex-wrap: wrap;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1rem;
    padding-top: 1rem;
    padding-bottom: 2rem;
  }
  .card-series {
    flex: 0 0 calc(100 / 6);
  }

  .container-blue-icon {
    background-color: #0282f9;
    height: 7rem;
    color: white;
    .icons {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 2rem;
      .icon {
        display: flex;
        align-items: center;
        gap: 0.4rem;
        img {
          width: 2.5rem;
          height: 3rem;
          object-fit: cover;
          object-fit: fill;
        }
      }
    }
  }
}
</style>
