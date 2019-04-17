<template>
  <div class="conterne">
    <span class="bxxmc">{{bxxmc}}</span>
    <span class="miko" >{{miko}}</span>
  <a href="https:baidu.com">  <img class="tp" :src="url" alt=""> </a> 
  <hr class="xhx" >
  <span class="pp" >{{pp}}</span>
  <span class="sx" >{{sx}}</span>
  <hr class="Xhx" >
  </div>
</template>
<script>
import fontsizeset from "@/fontsizeset";
export default {
  data() {
    return {
      bxxmc: "保险箱名称",
      miko:"MIKO保险箱",
        url:require("@/assets/切图/android/drawable-xxhdpi/back-2.png"),
        pp:"品牌",
        sx:"三星"
    };
  }
};
</script>
<style>
* {
  padding: 0;
  margin: 0;
}
.conterne {
  width: 7.5rem;
  height: 2.23rem;
  float: left;
  /* border: 1px solid black; */
}
.conterne .bxxmc {
  float: left;
  font-size: 0.28rem;
  margin-left: 0.3rem;
  margin-top: 0.43rem;
  color: #959595;
}
.conterne .miko{
    float: left;
    font-size: 0.28rem;
  margin-top: 0.43rem;
margin-left: 3.33rem;
color:#020202;
}
.conterne .tp{
        width: 0.2rem;
    height: 0.36rem;
    float: right;
    margin-right: 0.3rem;
    margin-top: 0.46rem;
}
.conterne .xhx{
    border: 0.01rem solid #d9d9d9;
    width: 6.9rem;
    float: left;
    margin-left: 0.3rem;
    margin-top: 0.39rem;
    background-color: #d9d9d9;
}
.conterne .pp{
      float: left;
  font-size: 0.28rem;
  margin-left: 0.3rem;
  margin-top: 0.4rem;
  color: #959595;
}
.conterne .sx{
      float: left;
    font-size: 0.28rem;
  margin-top: 0.4rem;
margin-left: 5.7rem;
color:#020202;  
}
.conterne .Xhx{
    width: 6.9rem;
    float: left;
    margin-left: 0.3rem;
    margin-top: 0.19rem;
    background-color: #d9d9d9;
    border: 0.01rem solid #d9d9d9;
}
</style>
