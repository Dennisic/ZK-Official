<template>
  <div class="home-page">
    <!-- <img src="./assets/header.png" class="header"/>
    <div class="text">Network the parallel</div>
    <div class="text">zk-based chain worlds</div> -->
  </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
.home-page{
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: url("./assets/ZK-2.gif") no-repeat center #000000;
  background-size: contain;
  text-align: center;
}
.header{
  margin-top: 30px;
  margin-bottom: 30px;
  height: 5vw;
}
.text{
  font-size: 4vw;
  font-weight: bold;
  /* color: #FFFFFF; */
  line-height: 82px;
  background-image: linear-gradient(137deg, #60638B 20%, #F9F9F9 50%, #60638B 80%, #F9F9F9 100%);
  -webkit-background-clip: text;
  color: transparent;
  text-align: center;
}
</style>
