<template>
  <div class="container">
    <Header />
    <Searchbar />
    <Footer />
  </div>
</template>

<script>
import Footer from "./components/Footer.vue";
import Header from "./components/Header.vue";
import Searchbar from "./components/Searchbar.vue";

export default {
  name: "App",
  components: {
    Footer,
    Header,
    Searchbar,
  },
};
</script>

<style>

html {
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
}
body {
  margin: 0;
  padding: 0;
  min-height: 100%;
  width: 100%;
}

.container {
  background-color: #eeeeee;
  display: inline;
  width: 100%;
}

</style>
