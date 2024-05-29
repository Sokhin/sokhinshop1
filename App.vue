<template>
  <div id="app">
    <SearchBar />
    <AdvertisePage />
    <ContentsPage />
    <ProductPage />
    <FooterPage />
  </div>
</template>

<script>
import SearchBar from "./components/SearchBar";
import AdvertisePage from "./components/AdvertisePage.vue";
import ContentsPage from "./components/ContentsPage.vue";
import ProductPage from "./components/ProductPage.vue";
import FooterPage from "./components/FooterPage.vue";
export default {
  name: "App",
  components: {
    SearchBar,
    AdvertisePage,
    ContentsPage,
    ProductPage,
    FooterPage,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  background-color: aliceblue;
}
</style>
