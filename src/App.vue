<template>
  <div>
    <HeaderPage />

    <MainPage />

    <FooterPage />
  </div>
</template>

<script>
import HeaderPage from "@/components/HeaderPage.vue";
import MainPage from "@/components/MainPage.vue";
import FooterPage from "@/components/FooterPage.vue";

export default {
  components: {
    HeaderPage,
    MainPage,
    FooterPage,
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-size: 0.8rem;
  font-family: "Montserrat", sans-serif;
}
.container {
  max-width: 900px;
  margin: auto;
  height: 100%;
}
</style>
