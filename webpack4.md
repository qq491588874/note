# 知识点

  ## 什么是WebPack
> Webpack 是一种模块打包工具

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

## @loder@
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

## [@插件PLUGINS@](https://webpack.js.org/plugins)  

- htmWebpackPlugin 插件会在打包结束后,自动生成一个index.html,并引入bundle.js
- clean-wbpack-plugin


## @SourceMap@
- 错误映射(不同模式影响打包时间)
- DevTool

## @WebpackDevServer@
- 作用:自动重新打包,从而提高开发效率


## @HMR(Hot Module Replacement) 热模块替换@

## @babel@ 用于将ES6语法转化成ES5语法,以兼容更多浏览器

## @TreeShaking@
- 作用:按需导入文件


## @开发环境跟产品环境@

## @Code Splitting@ 
- 代码分割
- 配置文件中配置:SplitChunksPlugin


## @LazyLoading@
-




