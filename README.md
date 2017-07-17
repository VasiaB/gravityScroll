# gravityScroll
移动端利用重力控制屏幕滚动，基于DOM


## Demo

[Demo 点击查看](http://go.163.com/2015/public/team/ningbo/gravityScroll/)

![qr-code](img/qr-code.png)

## 使用说明

引用组件
```javascript
<script src="js/jquery-1.9.1.min.js"></script>
<!-- 取消移动端点击延迟 -->
<script src="js/fastclick.js"></script>
<!-- 重力感应 -->
<script src="js/orienter.min.js"></script>
<!-- 配置 -->
<script src="js/gravityScroll.js"></script>
```

### JavaScript 初始化

```
// 初始化
$('.map').pos({
  // 起始位置
  'lastPageX': -100,
  // 开启循环
  'loop': true
});
```

### HTML

```html
<div class="map">
  <div class="map-box"></div>
</div>
```

### CSS

```css
.map-box{
  width: 2270px;
  height: 1030px;
  position: absolute;
  bottom: 0;
  top: 0;
  left: 0;
  margin: auto;
  background: url("../img/bg2.jpg") no-repeat center; 
}
```