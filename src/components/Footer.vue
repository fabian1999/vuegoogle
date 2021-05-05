<template>
  <div class="footer">
    <p>România</p>
    <hr />
    <ul class="horizontal-list-center">
      <li>Despre</li>
      <li>Publicitate</li>
      <li>Companii</li>
      <li>Cum functioneaza Cautarea</li>
      <li class="padding-list">Confidentialitate</li>
      <li class="padding-list">Termeni</li>
      <li class="padding-list">Setari</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  background-color: #f2f2f2;
  color: white;
  text-align: center;
  padding-bottom: 1.3%;
}

.horizontal-list-center {
  margin: auto;
}

.horizontal-list-center li {
  margin: 0 20px;
  display: inline-block;
  font-family: arial, sans-serif;
  font-size: 15px;
  color: rgba(0, 0, 0, 0.54);
}

.padding-list {
  padding-top: 1.3%;
}

.footer p {
  padding: 15px 30px;
  font-size: 15px;
  color: rgba(0, 0, 0, 0.54);
  text-align: left;
  margin: 0;
  font-family: arial, sans-serif;
}

hr {
  margin: 0;
  padding: 0;
  background-color: #dadce0;
  border: 0;
  height: 1px;
}
</style>
