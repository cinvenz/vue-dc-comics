<template>
  <main>
    <div class="container-black">
      <div class="container contents">
        &#8594; Contents goes here &#8592;
      </div>
    </div>
    <div class="container-blue-icon">
      <div class="container icons">
        <div class="icon">
          <img src="@/buy-comics-digital-comics.png" alt="">
          <span>DIGITAL COMICS</span>
        </div>
        <div class="icon">
          <img src="@/buy-comics-merchandise.png" alt="">
          <span>DC MERCHANDISE</span>
        </div>
        <div class="icon">
          <img src="@/buy-comics-subscriptions.png" alt="">
          <span>SUBSCRIPTION</span>
        </div>
        <div class="icon">
          <img src="@/buy-comics-shop-locator.png" alt="">
          <span>COMIC SHOP LOCATOR</span>
        </div>
        <div class="icon">
          <img src="@/buy-dc-power-visa.svg" alt="">
          <span>DC POWER VISA</span>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: 'MainPage',
};
</script>

<style lang="scss" scoped>
  main {
    .container-black {
      background-color: black;
      height: 14vh;
      font-size: 1.5rem;
      .contents {
      display: flex;
      align-items: center;
      color: white;
      }
    }
    .container-blue-icon {
      background-color: #0282F9;
      height: 18vh;
      color: white;
      .icons {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 2rem;
        .icon {
          display: flex;
          align-items: center;
          gap: .4rem;
          img {
            width: 2rem;
            object-fit: contain;
          }
        }
      }
    }
  }
</style>
