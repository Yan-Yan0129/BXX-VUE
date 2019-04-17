<template>
  <div class="header">
    <a class="tz" href="https:baidu.com">
      <img class="tp" :src="url" alt="1"> </a>
    <span class="bxxxq" >{{bxxxq}}</span>
  </div>
</template>
<script>
import fontsizeset from "@/fontsizeset";
export default {
  data() {
    return {
        url:require("@/assets/切图/android/drawable-xhdpi/back.png"),
        bxxxq:"保险箱详情",
    };
  }
};
</script>
<style>
* {
  padding: 0;
  margin: 0;
}
.header {
  width: 7.5rem;
  height: 0.88rem;
  background-color: black;
}
.header .tp{
    float: left;
    margin-top: 0.27rem;
    margin-left: 0.3rem;
    width: 0.2rem;
    height: 0.36rem;
}
.header .bxxxq{
    float: left;
    color: white;
    font-size: 0.32rem;
    margin-left: 2.47rem;
    margin-top: 0.27rem;
}
</style>
