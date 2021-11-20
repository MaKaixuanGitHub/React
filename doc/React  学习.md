# Reacts

[toc]



## P01-React 简介

1.什么是react？

> React是用于构建用户界面的 JavaScript库。

2.谁开发的？

> 由Facebook开发。

3.为什么要学习？

> 原生的 JavaScript 操作DOM繁琐，效率低。
> 使用 JavaScript 直接操作DOM，浏览器会进行大量的重绘重排。
> 原生的 JavaScript 没有组件化编码方案，代码复用效率低。

4.React 特点

> 采用组件化模式，声明式编码，提高开发效率以及组件复用率。
> 在React Native中可以使用React语法进行移动端开发。
> 使用虚拟DOM+优秀的Diffing算法，尽量减少真是的DOM交互。

## P02-Hello React入门案例

引入React库，顺序不能改变

~~~react
<!-- react 核心库 -->
<script src="https://cdn.staticfile.org/react/16.4.0/umd/react.development.js"></script>
<!-- react-dom 用于支持react操作DOM -->
<script src="https://cdn.staticfile.org/react-dom/16.4.0/umd/react-dom.development.js"></script>
<!-- babel 用于将JSX转为>JS -->
<script src="https://cdn.staticfile.org/babel-standalone/6.26.0/babel.min.js"></script>
~~~































































