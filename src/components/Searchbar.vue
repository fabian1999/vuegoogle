<template>
  <div class="center">
    <img class="logo-img" src="../pictures/Google_2015_logo.svg.png" />
    <input class="search-bar" />
    <div class="search-buttons">
      <button class="styled-buttons">Căutare Google</button>
      <button class="styled-buttons">Mă simt norocos</button>
    </div>
    <p class="google-details">
      Google oferit în: <a href="#">English</a> <a href="#">Magyar</a>
      <a href="#">Deutsch</a>
    </p>
  </div>
</template>

<script>
export default {
  name: "Searchbar",
};
</script>

<style scoped>
.center {
  margin: auto;
  width: 90vh;
  padding: 10px;
  text-align: center;
  padding-top: 10%;
}

.logo-img {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 60%;
  padding-bottom: 20px;
}

.search-bar {
  width: 90%;
  height: 35px;
  border: none;
  box-shadow: 0px 0px 0px 1px #ececec;
  border-radius: 20px;
  padding-left: 4%;
  padding-right: 4%;
  margin-bottom: 3%;
}

.search-bar:hover {
  box-shadow: 0px 0px 12px 5px #ececec;
}

.search-bar:focus {
  outline: none;
}

.search-buttons {
  padding-top: 20px;
}

.styled-buttons {
  height: 35px;
  width: 130px;
  border: none;
  background-color: #f8f9fa;
  border-radius: 5px;
}

.styled-buttons:hover {
  box-shadow: 0px 0px 1px 1px #ececec;
}

.google-details {
  padding-top: 20px;
  font-family: arial, sans-serif;
  font-size: 13px;
}

.google-details a {
  text-decoration: none;
  padding-left: 5px;
}

button {
    margin-left: 2px;
    margin-right: 2px;
}
</style>
