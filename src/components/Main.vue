<template>
  <div class="indexBackground">
    <template>
      <img src="./image/美食.jpeg" height="200" width="600" class="imageView">
      <div class="buttonDiv">
      <div class="singleButtonDiv">
        <div class="buttonText">签</div>
        <span>签到有礼</span>
      </div>
      <div class="singleButtonDiv">
        <div class="buttonText">会</div>
        <span>会员优惠</span>
      </div>
      <div class="singleButtonDiv">
        <div class="buttonText">茶</div>
        <span>清明茶叶</span>
      </div>
      <div class="singleButtonDiv">
        <div class="buttonText">果</div>
        <span>生鲜水果</span>
      </div>
      <div class="singleButtonDiv">
        <div class="buttonText">花</div>
        <span>浓郁花香</span>
      </div>
      <div class="singleButtonDiv">
        <div class="buttonText">补</div>
        <span>滋补养生</span>
      </div>
      </div>
      <div class="massageDiv">
        <img src="./image/消息.png" height="20" width="20" alt="" style="padding-right: 10px">
          亲爱哒上帝，本店默认为天天快递发货，祝购物愉快！！
      </div>
      <div class="socialPriceDiv"><b>本期力荐</b></div>
    </template>
    <div class="TabBarDiv">
      <div class="tabItemDiv">
        <img src="./image/首页.png" height="25" width="25">首页
      </div>
      <div class="tabItemDiv">
        <img src="./image/更多.png" height="20" width="20">商品分类
      </div>
      <div class="tabItemDiv">
        <img src="./image/更多.png" height="20" width="20">购物车
      </div>
      <div class="tabItemDiv lastItem">
        <img src="./image/更多.png" height="20" width="20">个人中心
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang='less'>
.indexBackground{
  height: 100%;
  width: 100%;
  padding: 0;
  .imageView{
    width: auto;
    height: auto;
    max-width: 100%;
    max-height: 100%;  
  }
  .buttonDiv{
    height: 150px;
    width: 100%;
    background-color: #FFFEF4;
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    align-items: center;
    .singleButtonDiv{
      width: 30%;
      height: 70px;
      .buttonText{
        color: white;
        font-weight: 700;
        font: 20px;
        background-color: #AC815C;
        width: 30px;
        height: 30px;
        border-radius: 50%;
        line-height: 30px;
        margin: 0 auto;
        margin-top: 10px;
      }
      span{
        font-size: 11px;
      }
    }
  }
  .massageDiv{
    color: #DD4A3D;
    background-color: rgba(255, 250, 240, 0.3);
    height: 30px;
    border: solid 1px #EFEFEF;
    align-items: center;
    display: flex;
    font-size: 14px;
    justify-content: center;
  }
  .socialPriceDiv{
    background-color: #F6F6F6;
    height: 40px;
    padding-top: 5px;
    color: #682F25;
  }
}
.TabBarDiv{
  position: fixed;
  width: 100%;
  height: 48px;
  left: 0px; bottom: 0;
  border: solid 1px #F0F0F0;
  .tabItemDiv{
    float: left;
    border-right: solid 1px #F0F0F0;
    width: 24.6%;
    height: 48px;
    text-align: center;
    font-size: 12px;
  }
  .lastItem{
      border: none;
    }
}
</style>
