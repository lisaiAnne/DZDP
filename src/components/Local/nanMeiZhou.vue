<template>
  <div class="nanMei">
    <div class="nav">
      <div class="place">
        <p class="hotPlace"><span>热门目的地</span><span>8个</span></p>
        <ul class="placeUl">
          <li><a href="#">布宜诺斯艾利斯</a></li>
          <li><a href="#">圣保罗</a></li>
        </ul>
        <ul class="placeUl">
          <li><a href="#">圣地亚哥</a></li>
          <li><a href="#">利马</a></li>
        </ul>
        <ul class="placeUl">
          <li><a href="#">里约热内卢</a></li>
          <li><a href="#">哥伦比亚</a></li>
        </ul>
        <ul class="placeUl">
          <li><a href="#">厄瓜多尔</a></li>
          <li><a href="#">库斯科</a></li>
        </ul>
      </div>
      <div class="place">
        <p class="hotPlace"><span>全部国家</span><span>13个</span></p>
        <ul class="placeUl">
          <li><a href="#">巴西</a></li>
          <li><a href="#">阿根廷</a></li>
        </ul>
        <ul class="placeUl">
          <li><a href="#">智利</a></li>
          <li><a href="#">秘鲁</a></li>
        </ul>
        <ul class="placeUl">
          <li><a href="#">乌拉圭</a></li>
          <li><a href="#">厄瓜多尔</a></li>
        </ul>
        <ul class="placeUl">
          <li><a href="#">哥伦比亚</a></li>
          <li><a href="#">委内瑞拉</a></li>
        </ul>
        <ul class="placeUl">
          <li><a href="#">圭亚那</a></li>
          <li><a href="#">巴拉丰</a></li>
        </ul>
        <ul class="placeUl">
          <li><a href="#">法术圭亚那</a></li>
          <li><a href="#">玻利维亚</a></li>
        </ul>
        <ul class="placeUl">
          <li><a href="#">苏里南</a></li>
        </ul>

      </div>
    </div>
  </div>

</template>

<script>
    export default {
        name: "nanMeiZhou"
    }
</script>

<style scoped>
  .nav{
    background:white;
    margin-left:1.07rem;
  }
  .hotPlace{
    display: flex;
    line-height:.51rem;

  }
  .hotPlace span:first-child{
    font-size:.15rem;
  }
  .hotPlace span:last-child{
    font-size:.13rem;
    color:#8a8a8a;
    margin-left:.05rem;
  }
  .placeUl{
    display: flex;
    font-size:.14rem;
  }
  .placeUl li{
    width:1.2rem;
    height:.36rem;
    color:#101010;
    text-align:center;
    margin-right:.08rem;
    margin-bottom:.08rem;
    line-height:.36rem;
    border:1px solid #ebebeb;
    border-radius: 5px;
  }
  .placeUl li span{
    font-size:.11rem;
    color:#ababab;
    margin-left:.05rem;
  }
</style>
