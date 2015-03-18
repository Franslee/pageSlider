# PageSlider #  
 
PageSlider 是一个基于zepto.js用于实现H5单页面跟随手指滑动切换的组件，目前支持页面上下滑动切换,支持移动端touch设备，支持通过transform3D启动GPU加速。

## DEMO ##

请用手机扫描以下二维码,在打开的页面上下滑动查看效果     
#![github](http://franslee.github.io/pageSlider/qr-code.png "pageSlider DEMO") 

## 用法 ##

HTML标签

```html
<div class="section sec1"></div>
<div class="section sec2"></div>
<div class="section sec3"></div>
<div class="section sec4"></div>
<div class="section sec5"></div>
<div class="section sec6"></div>
…
```

在页面中引入组件所需样式表文件pageSlider.css

```css
<link rel="stylesheet" href="../dist/pageSlider.css">
```

本组件基于zepto，需要在页面中引入zepto.js文件

```html
<script src='http://cdn.bootcss.com/zepto/1.1.4/zepto.min.js'></script>
```

引入pageSlider.js/pageSlider.min.js文件

```html
<script src='../dist/pageSlider.js'></script>
```

在页面DOM加载完毕之后，初始化组件

```js
$(function() {
	var pageSlider = PageSlider.case();
});
```

