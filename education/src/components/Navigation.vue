<template>
  <div id="content1">
    <div>
      <input type="text" id="searchw" />
      <label for="searchw">搜索</label>
    </div>
    <div id="overflow">
     sd
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
#overflow {
  overflow: scroll;
  overflow-x: hidden;
  height: 300px;
}
#content1 {
  float: left;
  width: 199px;
  background-color: brown;
}
#searchw {
  width: 156px;
  margin-bottom: 20px;
}
</style>