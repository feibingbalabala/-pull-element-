# 基于pull-element的上拉加载更多
上拉加载更多的实现思路虽说是一个挺简单的东西，但是要想用户体验好却不是那么简单。市面上我见到的就是[iscroll](https://github.com/cubiq/iscroll "iscroll") 插件，[refresher](http://www.jq22.com/jquery-info4469 "refresher")插件(基于iscroll)，[better-scroll](https://github.com/feibingbalabala/better-scroll "better-scroll")。这三款不过感觉都挺大的，最主要的是有BUG啊(比如我遇到的就是上拉，当手指移除屏幕以后整个滚动的部分就会弹不回来了，很尴尬)，自己造轮子把，又tm懒。
不过最近遇到了[pull-element](https://github.com/Lucifier129/pull-element "pull-element")这个触摸拖动元素的交互效果，不依赖其他插件，支持上下左右滚动哦。于是我就想改造成自己的轮子把。
