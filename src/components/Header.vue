<template>
  <div class="nav-bar">
    <ul class="horizontal-list">
      <li>Gmail</li>
      <li>Imagini</li>
      <li class="margin-left">
        <img
          src="https://cdn.iconscout.com/icon/free/png-512/apps-46-461702.png"
        />
      </li>
      <li>
        <img
          src="https://lh3.googleusercontent.com/ogw/ADGmqu_WLnXfFMfaBwsw4ify8JXDjRDBrmuy9Y4LGxD36Q=s32-c-mo"
          class="account-img"
        />
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
.horizontal-list {
  margin: auto;
  float: right;
  padding-top: 5px;
  padding-right: 5px;
}

.horizontal-list li {
  padding-left: 10px;
  display: inline;
  font-family: arial, sans-serif;
  font-size: 13px;
  height: 50px;
  line-height: 50px;
}

.margin-left {
  margin-left: 10px;
}

.margin-left img {
  height: 30px;
  vertical-align: middle;
}

.account-img {
  border-radius: 50%;
  vertical-align: middle;
  margin-right: 10px;
}
</style>
