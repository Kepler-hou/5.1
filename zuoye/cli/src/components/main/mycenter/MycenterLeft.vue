<template>
  <div class="mycenterleft">
    <div class="headimage">
      <div class="peopleimg">
        <img src="../../../assets/2.jpg" alt />
      </div>
      <div class="message">
        <span>罗密欧</span>
        <img src alt />
        <div>
          <p>信息完整度</p>
          <div class="progress"></div>
          <span>高</span>
        </div>
        <div class="contact_way">
          <img src="../../../assets/phone.png" alt />
          <img src="../../../assets/card.png" alt />
          <img src="../../../assets/email.png" alt />
        </div>
      </div>
    </div>
    <div class="surplus">
      <div class="embody">
        <span>申请提现</span>
      </div>
      <div class="money">
        <span>账户余额</span>
        <div>
          <span class="bold">248</span>
          <span>元</span>
        </div>
      </div>
    </div>
    <div class="attestation"></div>
  </div>
</template>
<script>
export default {
  name: "mycenterleft"
};
</script>
<style scoped>
* {
  padding: 0;
  margin: 0;
}
.mycenterleft {
  width: 400px;
  height: 500px;
  /* margin: 0 auto; */
  background-color: #ffffff;
}
.peopleimg img {
  width: 80px;
  height: 80px;
}
.message span {
  color: #333333;
  font-size: 14px;
  font-weight: 500;
}
.message {
  padding-left: 20px;
}

.surplus {
  border-top: 1px solid #f6f6f6;
  border-bottom: 1px solid #f6f6f6;
  display: flex;
  height: 100px;
}
.embody {
  flex: 1;
  width: 140px;
  height: 30px;
  background-color: #00aaff;
  border-radius: 20px;
  text-align: center;
  line-height: 30px;
  margin-top: 36px;
  margin-left: 40px;
}
.money {
  flex: 1;
  /* margin-left: 20px; */
  margin-top: 26px;
  margin-left: 40px;
}
.money span {
  color: #666666;
  font-size: 12px;
}
.headimage {
  padding: 20px 0px 15px 20px;
  display: flex;
  align-items: center;
}
.message > div > p {
  font-size: 11px;
  padding-top: 10px;
  color: #666666;
  display: inline-block;
}
.progress {
  width: 110px;
  background-color: #00aaff;
  border-radius: 15px;
  height: 7px;
  display: inline-block;
  margin-left: 10px;
  line-height: 5px;
}
.message > div > span {
  padding-left: 5px;
  color: #00aaff;
  font-size: 11px;
}
.contact_way > img {
  width: 15px;
  height: 15px;
  margin: 15px 6px 0px 0px;
}
.money .bold {
  font-size: 2em;
  font-weight: 500;
  color: #333333;
}
.embody>span {
    color: #f6f6f6;
}
</style>