<template>
  <main>
    <div class="container-black">
      <div class="main-img"></div>
      <div class="main-back">
        <div class="current-series">
          <p>CURRENT SERIES</p>
        </div>
        <div class="container cartoon-card">
          <CardSeries
            class=""
            v-for="objCard in arrCards"
            :key="objCard.series"
            :imgUrl="objCard.thumb"
            :name="objCard.series"
          />
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
  data() {
    return {
      arrCards: [
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
          price: "$19.99",
          series: "Action Comics",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
          price: "$3.99",
          series: "American Vampire 1976",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
          price: "$16.99",
          series: "Aquaman",
          type: "graphic novel",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
          price: "$2.99",
          series: "Batgirl",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$3.99",
          series: "Batman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$2.99",
          series: "Batman Beyond",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
          price: "$3.99",
          series: "Batman/Superman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
          price: "$4.99",
          series: "Batman/Superman Annual",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
          price: "$5.99",
          series: "Batman: The Joker War Zone",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
          price: "$6.99",
          series: "Batman: Three Jokers",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
          price: "$4.99",
          series: "Batman: White Knight Presents: Harley Quinn",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
          price: "$16.99",
          series: "Catwoman",
          type: "graphic novel",
        },
      ],
    };
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
    font-size: 0.7rem;
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
