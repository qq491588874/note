# 第1章 课程介绍

本章主要介绍课程的知识大纲，学习前提，讲授方式及预期收获。
-  1-1 课程简介

  ```vue
  var app = new Vue({
  	el: '#app',
  	data: {
  		content: "hello world!"
  	}
  })
  ```

# 第2章 Vue 起步

本章将快速讲解部分 Vue 基础语法，通过 TodoList 功能的编写，在熟悉基础语法的基础上，扩展解析 MVVM 模式及前端组件化的概念及优势。

-  2-1 课程学习方法

-  2-2 hello world

  ```
  <script>标签引入vue
  	<script src= './vue.js'></script>----引包
  	<div id="app"> {{content}}</div>----html中创建div
  	<script>(在script标签中创建vue实例)
  		var app = new Vue({
  				el: '#app', ----实例负责管理的内容
  				data: {
  						content: 'hello world!'
  				}
  		})
  	</script>
  	
  ```

  - VUE不推荐有任何DOM操作

-  2-3 开发TodoList（v-model、v-for、v-on）

  > ​	v-for
  >
  > ​	v-on:
  >
  > ​	v-model

-  2-4 MVVM模式

  - M(模型) V(视图) P(控制器) 模式:
  - M-V-VM(VUE就是VM层)
  - 开发者只需关心M层数据的处理
  - jQuire是面向DOM的开发,VUE是面向数据开发

-  2-5 前端组件化

  - 把整个页面切分成一个个部分,这些部分就可以说是组件
  - 组件化开发可以对后期维护有极大的提高

-  2-6 使用组件改造TodoList

  - 父组件向子组件传值

  >    全局注册组件
  >
  > ​     Vue.component("ti", {
  >
  > ​            props: ['content'],
  >
  > ​            template: "<li>{{content}}</li>"
  >
  > ​        })
  >
  > ​	局部注册组件
  >
  > ​		定义组件
  >
  > ​        var itc = {
  >
  > ​            props:['content'],
  >
  > ​            template: "<li>{{content}}</li>"
  >
  > ​        }
  >
  > ​		注册组件
  >
  > ​		var app = new Vue({
  >
  > ​            el: '#app',
  >
  > ​            components: {
  >
  > ​                itc ———在这里注册组件
  >
  > ​            },
  >
  > ​            data: {
  >
  > ​                list: [],
  >
  > ​                ipvalue: ''
  >
  > ​            })

-  2-7 简单的组件间传值

  - 父组件向子组件传值
  - 子组件向父组件传值

-  2-8 章节小结

  - 不懂就看VUE.js官方文档

    

# 第3章 Vue 基础精讲

本章通过精挑细选的案例，精讲 Vue 中的基础知识，包括实例、生命周期、指令、计算属性、方法、侦听器，表单等部分内容。

-  3-1 Vue实例
  - 通过var vm = new Vue({})创建Vue实例
-  3-2 Vue实例生命周期**试看**
-  3-3 Vue的模版语法
-  3-4 计算属性,方法与侦听器
-  3-5 计算属性的 getter 和 setter
-  3-6 Vue中的样式绑定
-  3-7 Vue中的条件渲染
-  3-8 Vue中的列表渲染
-  3-9 Vue中的set方法

- 

  ##### 第4章 深入理解 Vue 组件

  本章将深入讲解 Vue 组件使用的细节点，从父子组件的参数传递及校验入手，逐步深入到非父子组件间传值、插槽、作用域插槽、动态组件等内容的讲解。

  -  4-1 使用组件的细节点
  -  4-2 父子组件间的数据传递
  -  4-3 组件参数校验与非 props 特性
  -  4-4 给组件绑定原生事件
  -  4-5 非父子组件间的传值
  -  4-6 在Vue中使用插槽
  -  4-7 作用域插槽
  -  4-8 动态组件与 v-once 指令

- 

  ##### 第5章 Vue 中的动画特效

  本章将讲解 Vue 中的 Css 及 Js 动画原理，以及在 Vue 中如使用 Animate.css 及Velocity.js 动画库，在理解了基础动画原理后，本章还扩展了 Vue 中多元素及列表过渡效果实现的知识，并会带同学们学习如何对通用动画效果进行代码封装。...

  -  5-1 Vue动画 - Vue中CSS动画原理
  -  5-2 在Vue中使用 animate.css 库
  -  5-3 在Vue中同时使用过渡和动画
  -  5-4 Vue中的 Js 动画与 Velocity.js 的结合
  -  5-5 Vue中多个元素或组件的过渡
  -  5-6 Vue中的列表过渡
  -  5-7 Vue中的动画封装
  -  5-8 本章小节

- 

  ##### 第6章 Vue 项目预热

  本章首先讲解项目环境的基础配置，在此基础上分析工程代码目录结构，延展讲解 Vue中单文件组件及单页面应用路由的概念，最后将带大家整理项目目录，完成 stylus、reset.css 等基础工具及样式的引入，完成项目开发前的准备工作。...

  -  6-1 Vue项目预热 - 环境配置
  -  6-2 Vue项目预热 - 项目代码介绍
  -  6-3 Vue项目预热 - 单文件组件与Vue中的路由
  -  6-4 Vue项目预热 - 单页应用VS多页应用
  -  6-5 Vue项目预热 - 项目代码初始化

- 

  ##### 第7章 项目实战 - 旅游网站首页开发

  本章正式进入项目开发环节，将带大家完整的实现项目中的首页，涵盖的功能点包含header组件拆分、iconfont引入、多区块轮播、热销推荐及周末游等展示模块。

  -  7-1 Vue项目首页 - header区域开发
  -  7-2 Vue项目首页 - iconfont 的使用和代码优化
  -  7-3 Vue项目首页 - 首页轮播图
  -  7-4 Vue项目首页 - 图标区域页面布局
  -  7-5 Vue项目首页 - 图标区域逻辑实现
  -  7-6 Vue项目首页 - 热销推荐组件开发
  -  7-7 Vue项目首页 - 开发周末游组件
  -  7-8 Vue项目首页 - 使用 axios 发送 ajax 请求
  -  7-9 Vue项目首页 - 首页父子组组件间传值

- 

  ##### 第8章 项目实战 - 旅游网站城市列表页面开发

  本章将讲解景点详情页面的开发，主要讲解渐隐渐显 Header 组件的制作，公用组件的拆分，路由参数的获取与处理，以及递归组件的使用。在详情页面，我们还会对通用动画效果进行代码封装。

  -  8-1 Vue项目城市选择页 - 路由配置
  -  8-2 Vue项目城市选择页 - 搜索框布局
  -  8-3 Vue项目城市选择页 - 列表布局
  -  8-4 Vue项目城市选择页 - BetterScroll 的使用和字母表布局
  -  8-5 Vue项目城市选择页 - 页面的动态数据渲染
  -  8-6 Vue项目城市选择页 - 兄弟组件数据传递
  -  8-7 Vue项目城市选择页 - 列表性能优化
  -  8-8 Vue项目城市选择页 - 搜索逻辑实现
  -  8-9 Vue项目城市选择页 - Vuex实现数据共享
  -  8-10 Vue项目城市选择页 - Vuex的高级使用及localStorage
  -  8-11 Vue项目城市选择页 - 使用keep-alive优化网页性能

- 

  ##### 第9章 项目实战 - 旅游网站详情页面开发

  本章将讲解景点详情页面的开发，主要讲解渐隐渐显Header组件的制作，公用组件的拆分，路由参数的获取与处理，以及递归组件的使用。在详情页面，我们还会对通用动画效果进行代码封装。

  -  9-1 Vue项目详情页 - 动态路由和banner布局
  -  9-2 Vue项目详情页 - 公用图片画廊组件拆分
  -  9-3 Vue项目详情页 - 实现Header渐隐渐显效果
  -  9-4 Vue项目详情页 - 对全局事件的解绑
  -  9-5 Vue项目详情页 - 使用递归组件实现详情页列表
  -  9-6 Vue项目详情页 - 动态获取详情页面数据
  -  9-7 Vue项目详情页 - 在项目中加入基础动画

- 

  ##### 第10章 实战项目 - 项目的联调，测试与发布上线

  本章将以公司级别项目的要求，给大家讲解当项目开发完成后，开发人员进行联调，测试，及发布的详细流程，同时点出过程中可能遇到的问题及修复方案。另外，还会给大家补充讲解异步组件的知识点，通过使用异步组件，我们可以大幅提高大型项目的首屏速度。最后，我们将给大家讲解，在这么课程学习完之后，继续深入学习Vue的方...

  -  10-1 Vue项目的联调测试上线 - 项目前后端联调
  -  10-2 Vue项目的联调测试上线 - 真机测试
  -  10-3 Vue项目的联调测试上线 - 打包上线
  -  10-4 Vue项目的联调测试上线 - 异步组件实现按需加载
  -  10-5 Vue项目的联调测试上线 - 课程总结与后续学习指南