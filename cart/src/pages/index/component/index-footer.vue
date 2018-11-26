<template>
    <ul class="footer border-top">
       <li class="footer-li">
            <i class="iconfont icon-home footer_icon"></i>
            <p class="tab-name">首页</p>
       </li>
        <li class="footer-li">
            <i class="iconfont icon-cartfill footer_icon"></i>
            <p class="tab-name">购物车</p>
        </li>
        <li class="footer-li">
            <i class="iconfont icon-my footer_icon"></i>
            <p class="tab-name">我的淘宝</p>
        </li>
        <li class="footer-li">
            <i class="iconfont icon-like footer_icon"></i>
            <p class="tab-name">心水</p>
        </li>
        <li class="footer-li">
            <i class="iconfont icon-more_light footer_icon"></i>
            <p class="tab-name">更多</p>
        </li>
    </ul>
</template>

<script>
export default {
  name: 'index-footer'
}
</script>

<style lang="stylus" scoped>
    .footer
        width 100%
        height .9rem
        position fixed
        left 0
        bottom 0
        display flex
        justify-content space-around
        align-items center
        padding-top .1rem
        .footer-li
            display flex
            flex-direction column
            justify-content center
            .tab-name
                font-size .26rem
                line-height .5rem
</style>
