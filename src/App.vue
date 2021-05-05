<template>
  <html>
    <body>
      <div class="container">
        <Header />
      </div>
    </body>
  </html>
</template>

<script>
import Header from "./components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

<style>

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

html {
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
}
</style>
