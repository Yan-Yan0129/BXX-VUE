<template>
    <div class="footer">
        <span class="xlh" >{{xlh}}</span>
        <span class="lm" >{{lm}}</span>
  <hr class="xhx">
  <span class="sbip" >{{sbip}}</span>
  <span class="sz" >{{sz}}</span>
  <hr class="xhx">
    <span class="gtbb" >{{gtbb}}</span>
  <span class="Sz" >{{Sz}}</span>
  <hr class="xhx">
    <span class="ljzt" >{{ljzt}}</span>
    <span class="ylj" >{{ylj}}</span>
  <hr class="xhX">

    </div>
</template>
<script>
import fontsizeset from "@/fontsizeset";
export default {
    data(){
        return{
            xlh:"序列号",
            lm:"GFRGR44FDFDFD",
            sbip:"设备IP",
            sz:"192.168.1.1",
            gtbb:"固态版本",
            Sz:"V2.01245",
            ljzt:"连接状态",
            ylj:"已连接"
        }
    }
}
</script>
<style>
*{
    padding: 0;
    margin: 0;
}
.footer .xlh{
      float: left;
  font-size: 0.28rem;
  margin-left: 0.3rem;
  margin-top: 0.43rem;
  color: #959595;   
}
.footer .lm{
          float: left;
    font-size: 0.28rem;
  margin-top: -0.35rem;
margin-left: 4.85rem;
color:#020202;  
}
.footer .xhx{
    border: 0.01rem solid #d9d9d9;
    width: 6.9rem;
    float: left;
    margin-left: 0.3rem;
    margin-top: 0.39rem;
    background-color: #d9d9d9;
}
.footer .sbip{
          float: left;
  font-size: 0.28rem;
  margin-left: 0.3rem;
  margin-top: 0.43rem;
  color: #959595; 
}
.footer .sz{
          float: left;
    font-size: 0.28rem;
  margin-top: -0.35rem;
margin-left: 5.65rem;
color:#020202;  
}
.footer .gtbb{
      float: left;
  font-size: 0.28rem;
  margin-left: 0.3rem;
  margin-top: 0.43rem;
  color: #959595;   
}
.footer .Sz{
          float: left;
    font-size: 0.28rem;
  margin-top: -0.35rem;
margin-left: 5.95rem;
color:#020202;  
}
.footer .ljzt{
      float: left;
  font-size: 0.28rem;
  margin-left: 0.3rem;
  margin-top: 0.43rem;
  color: #959595;   
}
.footer .ylj{
          float: right;
    font-size: 0.28rem;
  margin-top: 0.43rem;
margin-right: -0.8rem;
color:#020202;  
}
.footer .xhX{
    border: 0.01rem solid #d9d9d9;
    width: 7.5rem;
    float: left;
    /* margin-left: 0.3rem; */
    margin-top: 0.39rem;
    background-color: #d9d9d9;
}
</style>

