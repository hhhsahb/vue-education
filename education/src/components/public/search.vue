<template>
  <span>
    <label for="search" id="searchimage">{{searchimage}}</label>
    <input type="text" id="search" />
  </span>
</template>

<script>
export default {
    data() {
    return {
      home: "首页",
      search: "搜索",
      id: "我的",
      searchimage: "搜索"
    };
  }
};
</script>

<style>
#searchimage {
  margin-right: 50px;
  float: right;
}
#search {
  float: right;
}
</style>