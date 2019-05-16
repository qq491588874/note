# 知识点

> 视频目录
>
> - ##### 第1章 课程导学
>
>   *掌握Webpack越来越成为前端工程师的标配技能，本章会对课程整体进行介绍，打消你的学习疑虑。*
>
>   - 1-1 课程导学
>
> - **第2章 Webpack 初探**
>
>   *本章通过清晰易懂的例子，带你了解 Webpack 的产生背景，以及其能够解决的问题。在此基础上，完成开发环境的搭建，Webpack 的安装，并进行最基础的 Webpack 使用讲解。*
>
>   - 2-1 webpack 究竟是什么？
>   -  2-2 什么是模块打包工具？
>   -  2-3 Webpack的正确安装方式
>   -  2-4 使用Webpack的配置文件
>   -  2-5 浅析 Webpack 打包输出内容
>
> - ##### 第3章 Webpack 的核心概念
>
>   *本章讲解 Webpack 中的一些核心概念，从 Loader 与 Plugin 开始，带你学明白 Webpack 的运行机制，然后逐步深入，扩展衍生出 SoureMap， HMR， WDS 等常见概念。本章课程学习过程中，额外增加了对 Webpack 官方文档的查阅方式讲解，帮助大家学会查阅文档。*
>
>   -  3-1 什么是 loader
>   -  3-2 使用 Loader 打包静态资源（图片篇）
>   -  3-3 使用 Loader 打包静态资源（样式篇 - 上）
>   -  3-4 使用 Loader 打包静态资源（样式篇 - 下）
>   -  3-5 使用 plugins 让打包更便捷
>   -  3-6 Entry 与 Output 的基础配置
>   -  3-7 SourceMap 的配置
>   -  3-8 使用 WebpackDevServer 提升开发效率
>   -  3-9 Hot Module Replacement 热模块更新（1）
>   -  3-10 Hot Module Replacement 热模块更新（2）
>   -  3-11 使用 Babel 处理 ES6 语法（1）
>   -  3-12 使用 Babel 处理 ES6 语法（2）
>   -  3-13 Webpack 实现对React框架代码的打包
>
> - ##### 第4章 Webpack 的高级概念
>
>   *本章接第三章内容，继续讲解 Webpack 中难度更大的知识点，包含了 Tree Shaking，Code Spliting，打包环境区分，缓存，shimming 等内容，帮助你继续扩展 Webpack 的基础知识面。*
>
>   -  4-1 Tree Shaking 概念详解**试看**
>   -  4-2 Develoment 和 Production 模式的区分打包
>   -  4-3 Webpack 和 Code Splitting（1）
>   -  4-4 Webpack 和 Code Splitting（2）
>   -  4-5 SplitChunksPlugin 配置参数详解（1）
>   -  4-6 SplitChunksPlugin 配置参数详解（2）
>   -  4-7 Lazy Loading 懒加载，Chunk 是什么？
>   -  4-8 打包分析，Preloading, Prefetching
>   -  4-9 CSS 文件的代码分割
>   -  4-10 Webpack 与浏览器缓存( Caching )
>   -  4-11 Shimming 的作用
>   -  4-12 环境变量的使用方法
>
> - ##### 第5章 Webpack 实战配置案例讲解
>
>   ​	*本章通过库文件打包，PWA项目打包，TypeScript打包支持等实战常见 Webpack 配置案例，带大家了解最新前端工程化常识，并在实例实现的过程中，巩固前三章节的基础知识点。同时章节末尾进行了 Webpack 打包性能优化的内容，帮助同学们了解如何在打包速度过慢时进行合理的打包过程优化。*
>
>   -  5-1 Library 的打包
>   -  5-2 PWA 的打包配置
>   -  5-3 TypeScript 的打包配置
>   -  5-4 使用 WebpackDevServer 实现请求转发
>   -  5-5 WebpackDevServer 解决单页面应用路由问题
>   -  5-6 EsLint 在 Webpack 中的配置（1）
>   -  5-7 EsLint 在 Webpack 中的配置（2）
>   -  5-8 webpack 性能优化(1)
>   -  5-9 webpack 性能优化(2)
>   -  5-10 Webpack 性能优化(3)
>   -  5-11 Webpack 性能优化(4)
>   -  5-12 webpack性能优化(5)
>   -  5-13 多页面打包配置
>
> - ##### 第6章 Webpack 底层原理及脚手架工具分析
>
>   *本章首先讲解如何自己实现 Webpack 中的 Loader 和 Plugin 的扩展。在了解 Webpack 扩展机制后，近一步深入 Webpack 底层，通过编码，实现了类似 Webpack 的简单打包工具，在此过程中，让同学们能够真正理解打包过程中的各种复杂概念及底层原理。*
>
>   -  6-1 如何编写一个 Loader（1）
>   -  6-2 如何编写一个 Loader（2）
>   -  6-3 如何编写一个 Plugin
>   -  6-4 Bundler 源码编写（模块分析 1）
>   -  6-5 Bundler 源码编写（模块分析 2）
>   -  6-6 Bundler 源码编写（ Dependencies Graph ）
>   -  6-7 Bundler 源码编写（ 生成代码 ）
>
> - ##### 第7章 Create-React-App 和 Vue-Cli 3.0脚手架工具配置分析
>
>   ​	*最后一章增加了对 Create-React-App 和 Vue-Cli 3.0 两个前端脚手架工具中 Webpack 配置内容的分析，帮助同学了解不同脚手架工具设计的出发点，和配置的技巧。*
>
>   - 7-1 通过 CreateReactApp 深入学习 Webpack 配置（1）
>   -  7-2 通过 CreateReactApp 深入学习 Webpack 配置（2）
>   -  7-3 Vue CLI 3 的配置方法及课程总结（1）
>   -  7-4 Vue CLI 3 的配置方法及课程总结（2）

## 安装
- 需要安装[node](https://nodejs.org/zh-cn/)
- 安装node的时候已经安装npm
```
mkdir webpack-demo
cd webpack-demo
npm init -y
npm install webpack --save-dev
npm install webpack-cli --save-dev
```
> 注意:
> - 不能安装全局,需要 -D安装  
> - 需要安装webpack和webpack-cli 

# 配置内容

## loder
- webpack默认只认得JS文件,需要打包.css .jpg等其他后缀文件,需要安装其他loder插件  
- 在webpack.config.js文件中设置
```es6
const path = require('path');

module.exports = {
    mode: 'development',[{
        test: /\.jpg$/,
        use: {
            loder: 'url-loader',
            options: {
            }
        }
    }]
    entry: ['./path'],
    output: {
        path: './path',
        filename: 'filename'
    },
    module: {
        rules: 
    }
}
```

> - file-loader
> - url-loader
> - style-loader
> - css-loader  
> 
> 需要打包的文件类型包括:图片,样式,字体  


[官方关于loader介绍](https://webpack.js.org/loaders/)

## [插件PLUGINS](https://webpack.js.org/plugins)  

- htmWebpackPlugin 插件会在打包结束后,自动生成一个index.html,并引入bundle.js
- clean-wbpack-plugin


## SourceMap
- 错误映射(不同模式影响打包时间)
- DevTool

## WebpackDevServer
- 作用:自动重新打包,从而提高开发效率

## HMR

- (Hot Module Replacement) 热模块替换

## babel

 用于将ES6语法转化成ES5语法,以兼容更多浏览器

## 

## TreeShaking
- 作用:按需导入文件


## 开发环境跟产品环境

## Code Splitting 
- 代码分割
- 配置文件中配置:SplitChunksPlugin
- CSS代码分割：MiniCssExtractPlugin（插件）会启用热启动开发环境不用，发布产品的时候才用


## LazyLoading
- import 语句引入的文件，打包分割的时候会懒加载
- filename 和 chunks filename分别
- chunks



## Shimming@垫片



## 环境变量



## Library打包

- libraryTarget: 'umd' 允许通过任何文件引用方式引用这个库
- library: 'root' ——通过<script>标签引用 
- 可以打包自己的库上传npm



## PWA 的打包配置

- Progressive Web Application作用：用户加载过一次页面，当服务器挂掉的时候，页面有缓存，可以展现，提升用户体验
- 安装第三方模块 "workbox-webpack-plugin"(谷歌封装好的插件)

## TypeScript的打包配置

- TS是微软开发的JS高级版的文件，在开发的时候可以更好提示错误

## axios

- 发送Ajax请求

- 发送Ajax请求的时候一般不会用绝对路径

##　DevServer

- 配置proxy可以让文件在开发环境和生产环境中的后端请求地址不同
- historyApiFallback解决单页面应用路由问题

## ESLint 

- 是一个规范项目中代码的工具
- 在webpack中使用可以用eslint-loader的加载器
- 打包的时候每次都检测会降低打包速度，实际工作中是打包上传仓库的时候才会检测(git 钩子)

##  提升打包文件速度

1. 升级node、npm、yarn
2. 使用loader的范围尽可能少
3. 插件尽可能精简和确保可靠(例如尽量用官网推荐的)
4. resolve参数合理配置

##  webpack跟脚手架关系

- 脚手架工具就是一个初始化项目基本文件配置的工具
- 脚手架工具已经默认配置好webpack中的基本配置
- vue-cli3底层也是webpack4，但大部分都是封装好的API，需要去到[vue-cli官网](https://cli.vuejs.org/zh/config/)中查看具体使用方法.

