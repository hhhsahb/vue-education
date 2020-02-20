<template>
  <div id="hear">
    <span>
      <a id="home" href="#">{{home}}</a>
    </span>
    <span>
      <a id="setting" href="#">{{setting}}</a>
    </span>
    <search></search>
  </div>
</template>

<script>
import search from "./public/search.vue";
export default {
  components: {
    search
  },
  data() {
    return {
      home: "首页",
      search: "搜索",
      setting: "设置",
      searchimage: "搜索"
    };
  }
};
</script>

<style>
* {
  font-size: 18px;
}
#hear {
  background-color: rgba(15, 136, 216, 0.918);
  height: 50px;
}
#hear #home {
  float: left;
}

#hear #setting {
  float: right;
}
</style>