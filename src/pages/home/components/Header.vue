<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-icon">&#xe624</div>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632</span>
      输入城市景点/游玩/主题
    </div>
    <div class="header-right">
      城市
      <span class="iconfont arrow-icon">&#xe64a</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeHeader"
};
</script>

<style lang="stylus" scoped>
// @import '~@/assets/styles/varibles.styl'
@import '~styles/varibles.styl'

.header 
  display: flex;
  line-height: 0.86rem;
  background-color: $bgColor;
  color: #fff;
  .header-left 
    width: 0.64rem;
    float: left;
    .back-icon
      text-align center
      font-size .4rem
  .header-input
    flex: 1;
    height: 0.64rem;
    line-height: 0.64rem;
    margin-top: 0.12rem;
    margin-left: 0.2rem;
    padding-left .2rem
    background-color: #ffffff;
    border-radius: 0.1rem;
    color: #cccccc;
  .header-right 
    width: 1.24rem;
    float: right;
    text-align: center;
    .arrow-icon
      margin-left -.04rem
      font-size .24rem

</style>
