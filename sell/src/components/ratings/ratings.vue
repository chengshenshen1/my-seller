<template>
  <div class="ratings">
    <div class="ratings-content">
      <div class="overview">
        <div class="overview-left"></div>
        <div class="overview-right"></div>
      </div>
    </div>
  </div>
</template>

<script type="es6">
 export default{};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" rel="stylesheet/stylus">
  .ratings
    position absolute
    top 174px
    left 0
    bottom 0
    width 100%
    overflow hidden
    .overview
      display flex
      padding 18px 0
      .overview-left
        flex 0 0 137px
        width 137px
        border-right 1px solid rgba(7, 17, 27, 0.1)
      .overview-right
        flex 1
</style>
