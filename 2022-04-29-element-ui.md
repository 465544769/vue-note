# element-ui

## 安装 element-ui (饿了么 ui)
```
yarn add element-ui -S
```
或
```
npm install element-ui -S
```

如果网络条件良好，也可以用引入 CDN
```html
<!-- 引入样式 -->
<link rel="stylesheet" href="https://unpkg.com/element-ui/lib/theme-chalk/index.css">
<!-- 引入组件库 -->
<script src="https://unpkg.com/element-ui/lib/index.js"></script>
```

## 使用
```js
import Vue from 'vue';
import ElementUI from 'element-ui';

Vue.use(ElementUI);

new Vue({
  render: h => h(App)
});
```


## 个人认为好玩的组件
+ Message 消息提示
+ Notification 通知
+ Popconfirm 气泡确认框
+ Switch 开关
+ Progress 进度条
+ Carousel 走马灯

**[饿了么ui官网](https://element.eleme.io/#/zh-CN/component/installation)**