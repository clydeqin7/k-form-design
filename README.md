


# 表单设计器 k-form-design

<p align="center">
  <a href="https://github.com/vuejs/vue">
    <img src="https://img.shields.io/badge/vue-2.6.10-brightgreen.svg" alt="vue">
  </a>
  <a href="https://github.com/vueComponent/ant-design-vue">
    <img src="https://img.shields.io/badge/Ant%20Design%20Vue-1.3.14-blue" alt="ant-design-vue">
  </a>
  <a href="https://github.com/Kchengz/k-form-design/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/mashape/apistatus.svg" alt="license">
  </a>
</p>

## 简介
基于vue和ant-design-vue实现的表单设计器，样式使用less作为开发语言，主要功能是能通过简单操作来生成配置表单，生成可保存的JSON数据，并能将JSON还原成表单，使表单开发更简单更快速

- [github](https://github.com/Kchengz/k-form-design)
- [码云](https://gitee.com/kcz66/k-form-design)
- [预览地址](http://cdn.kcz66.com/k-form-design.html)
- [文档地址Github Pages](http://www.kcz66.com/k-form-design/#/)
- [文档地址Gitee Pages](http://kcz66.gitee.io/k-form-design/#/)

## 特性
- 可视化配置页面
- 提供栅格、表格等布局
- 布局嵌套使用
- 表单自定义样式(以行内样式插入)
- 提供预览、保存、生成json、生成可执行代码等操作
- 支持表单验证
- 快速获取表单数据
- 自定义组件插入
- 提供高级控件
- 自定义主题色

## 组件
- KFormDesign 表单设计器（基于可视化操作快速设计出表单页面，生成配置json或页面）
- KFormBuild 表单构建器（根据设计器中获取的配置json数据，快速构建出表单页面）



## 安装
```
# 使用yarn 
yarn add k-form-design

# 使用npm 
npm i k-form-design --save
```

## 引入组件
``` javascript
// 在main.js引入

import KFormDesign from 'k-form-design'
import 'k-form-design/lib/k-form-design.css'
Vue.use(KFormDesign)
```

## 使用组件
``` javascript
<template>
  <div>
   <k-form-design />
  </div>
</template>
```

<!-- <p style="color:#ca6820;">
说明，该项目已经把所有需要的依赖全部打包了，包括UI组件，无需额外引入依赖即可使用，但是包的体积增大了许多
</p>	 -->


<!-- 
![1.jpg](https://i.loli.net/2019/09/29/X2h9Kji5HpC6ZdB.png)
![2.jpg](https://i.loli.net/2019/09/29/OzBGS6F2ZmflMCw.png)
![3.jpg](https://i.loli.net/2019/09/29/oYOjwT3qUr2SMmA.png)
![4.jpg](https://i.loli.net/2019/09/29/JtCDZELxe3r5ARl.png)
![5.jpg](https://i.loli.net/2019/09/29/NTGmdoDPXvqHJMe.png) -->
<!-- ## 支持
如果你发现了新的bug或者有新的feature request，请新建一个issue -->
## 交流
点击链接加入qq群聊，可以直接提问及反馈bug
[【k-form-desgin交流群：1020643215】](https://jq.qq.com/?_wv=1027&k=5BeoFAr)

License
---
[MIT](https://github.com/Kchengz/k-form-design/blob/master/LICENSE)
Copyright (c) 2019 Kchengz