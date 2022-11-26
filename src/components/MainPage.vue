<template>
  <main>
    <div class="container-black">
      <div class="main-img"></div>
      <div class="current-series"></div>
      <div class="container cartoon-card"></div>
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
export default {
  name: "MainPage",
};
</script>

<style lang="scss" scoped>
main {
  .container-black {
    background-color: black;
    font-size: 1.5rem;
    .main-img {
      background-image: url(../../public/jumbotron.jpg);
      background-position: 0 2%;
      background-size: cover;
      background-repeat: no-repeat;
      height: 17rem;
    }
  }
  .container-blue-icon {
    background-color: #0282f9;
    height: 8rem;
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
          width: 2rem;
          object-fit: contain;
        }
      }
    }
  }
}
</style>
