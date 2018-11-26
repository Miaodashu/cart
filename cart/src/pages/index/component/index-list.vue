<template>
    <div class="list">
        <ul>
            <li class="list-li">
                <div class="list-top border-bottom">
                    <div class="top-left"><label for="selectStoreAll_li" class="radio-label">
                        <input type="checkbox" id="selectStoreAll_li" class="select_radio">
                        <i class="iconfont radio_icon icon-round"></i>
                    </label><div class="logo"></div><span>上海世纪出版官方旗舰店</span></div>
                    <div class="top-right">
                        <span class="span border-right">领劵</span>
                        <span>编辑</span>
                    </div>
                </div>
                <div class="list-bottom">
                    <div class="active-wraper">
                        <div class="active">本地活动</div>
                        <div class="active-content">满68元，享包邮</div>
                    </div>
                </div>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
  name: 'index-list'
}
</script>

<style lang="stylus" scoped>

    .list-top
        display flex
        align-items center
        height .6rem
        padding 0 .24rem
        box-sizing border-box
    .radio-label
        position relative
        input
            width .44rem
            height .44rem
            opacity 0
            position absolute
        .iconfont
            font-size .44rem !important
    .logo
        width .32rem
        height .32rem
        margin 0 .2rem
        background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACQAAAAkCAMAAADW3miqAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAyRpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADw/eHBhY2tldCBiZWdpbj0i77u/IiBpZD0iVzVNME1wQ2VoaUh6cmVTek5UY3prYzlkIj8+IDx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IkFkb2JlIFhNUCBDb3JlIDUuMy1jMDExIDY2LjE0NTY2MSwgMjAxMi8wMi8wNi0xNDo1NjoyNyAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvIiB4bWxuczp4bXBNTT0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wL21tLyIgeG1sbnM6c3RSZWY9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9zVHlwZS9SZXNvdXJjZVJlZiMiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIENTNiAoTWFjaW50b3NoKSIgeG1wTU06SW5zdGFuY2VJRD0ieG1wLmlpZDpFRjQ4QTZBMjczMkYxMUU1OTIxNEVBNEM3N0VGQTM4QiIgeG1wTU06RG9jdW1lbnRJRD0ieG1wLmRpZDpFRjQ4QTZBMzczMkYxMUU1OTIxNEVBNEM3N0VGQTM4QiI+IDx4bXBNTTpEZXJpdmVkRnJvbSBzdFJlZjppbnN0YW5jZUlEPSJ4bXAuaWlkOkVGNDhBNkEwNzMyRjExRTU5MjE0RUE0Qzc3RUZBMzhCIiBzdFJlZjpkb2N1bWVudElEPSJ4bXAuZGlkOkVGNDhBNkExNzMyRjExRTU5MjE0RUE0Qzc3RUZBMzhCIi8+IDwvcmRmOkRlc2NyaXB0aW9uPiA8L3JkZjpSREY+IDwveDp4bXBtZXRhPiA8P3hwYWNrZXQgZW5kPSJyIj8+cikVKAAAAwBQTFRF0Ds6aWFg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")
        background-repeat no-repeat
        background-size contain
    .top-left
        display flex
        align-items center
        justify-content space-between
    .top-right
        font-size .26rem
        margin 0 0 0 1rem
        span
            padding 0 .1rem
        .span
            border-color #000
    .active-wraper
        display flex
        align-items center
        padding .2rem .4rem
        box-sizing border-box
        .active
            padding .01333rem .02667rem
            font-size 12px
            color #f50
            border 1px solid #f50
            border-radius 4px
            margin-right .3rem
</style>
