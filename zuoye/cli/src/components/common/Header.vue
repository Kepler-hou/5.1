<template>
  <div class="header">
    <div class="headerconnet">
        <div class="logo">
        <img src="../../assets/logo1.jpg" alt="">
      </div>
      <div class="logoright">
        <img src="../../assets/headimg.png" alt="">
        <span>罗密欧</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name:"Header"
}
</script>

<style>
*{
  padding: 0px;
  margin: 0px;
}
.header{
  /* width: 1366px; */
  background-color: #333333;
  box-shadow: 2px 2px 6px #eaeaea;
 
}
.headerconnet{
  line-height: 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0px 90px;
}
.logo{
  float: left;
}

.logo img{
  display: block;
  height: 40px;
}
.logoright{
  margin-right: 105px;
}


.logoright img{
  float: left;
  height: 40px;
}
.logoright>span{
  color: #f0f0f0;
  margin-left: 5px;
  font-size: 6px;
}


</style>
