<template>
    <div class="myHeader border-bottom" >
        <div class="icon">＜</div>
        购物车（）
    </div>
</template>

<script>
export default {
  name: 'index-header'
}
</script>

<style lang="stylus" scoped>
    .myHeader
        width 100%;
        height .6rem
        line-height .6rem
        padding .24rem
        text-align center
        font-size .28rem
        font-weight bold
        position relative
        .icon
            float left
            height .6rem
            font-size .28rem
            line-height .6rem
            font-weight bold
            position absolute
            left .24rem
            top 0
            bottom 0
            margin auto
</style>
