# book-learning-javascript
some notes and codes for the book Learning JavaScript.

JavaScript学习指南

#### 第1章 第一个应用
1.HTML5和HTML的区别？浏览器如何运行HTML5？

2.什么是CDN？<br>
公共的内容分发网络，content delivery network

3.什么是严格模式？<br>
```
use strict;
```

#### 第2章 JavaScript开发中的常用工具
4.Node允许在浏览器之外的地方运行JavaScript。

5.Gulp、Grunt和webpack的区别？<br>
Gulp是一个构建工具，可以将开发过程中的一些常用任务自动化。

6.Babel编译转换器，可以将ES6的代码转换为便于使用的ES5代码。

7.ESLint，一个可以避免常见错误的格式检查工具。

8.常见的终端工具bash，内嵌在shell（终端的图形用户界面）中，是Linux或OSX操作系统的默认终端。

9.bash、shell、cmd的关系和区别？

10.npm一般结合Node使用，作为项目的包管理工具。<br>
npm支持两种级别的安装包：全局和本地，全局的安装包通常是开发过程中的命令行工具，本地安装包用于具体的项目。<br>
npm通过package.json文件来管理安装的模块。<br>
依赖分为常规依赖和开发依赖。开发依赖是指只在项目构建时需要的依赖，程序运行时不需要。<br>
安装依赖时需要在命令后加--save或--saveDev，否则虽然会安装，但不会出现在package.json中。<br>

11.ES6和ES5的区别？各个支持的浏览器版本？<br>
let、解构赋值、函数参数默认值、箭头符号
