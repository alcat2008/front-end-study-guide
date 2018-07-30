# 前端学习指南

技术是一种载体，在它之上是对整个体系的认知，如何精进呢，Winter 的文章 [一个前端的自我修养
](http://taobaofed.org/blog/2016/03/23/the-growth-of-front-end/)，不容错过！

学习曲线遵循

```javascript

`JavaScript (ES5/6)` ===> `React` => `React Native` => ------|
         |            |       |                     |        |
        `FP`          |       ==> `Flux/Redux`  ==> |        |
                      |                                      |
                     ===> `Vue` => `Vuex` => ----------------|
                                                             |
                                                             |
`HTML` => `HTML5`   ===>     `Mental Model`  <===  ----------|
                     |           |
                     |           |
                     |        `Design` ===> `Art` ===> ...
                     |
`CSS` => `CSS3` => `LESS`
```

本文重在 “术”，追求的是广度，要想继续学习，在前端领域深入耕耘、探索，请参见以下内容：

- [“道”](./Advanced.md) —— 有一些技术背后的原理阐述、架构思考、编程方法论等。
- [“法”](./Implemention.md) —— 对前端细分领域的思考，注重深度，比如动画等。

另外，微信作为一个独立的开发体系，参见 [Wechat](./Wechat.md)

--------------------------------------------------------------------------------

## 概览

[How it feels to learn JavaScript in 2016](https://hackernoon.com/how-it-feels-to-learn-javascript-in-2016-d3a717dd577f#.ifom7kt4c)

中文版 => [在 2016 年学 JavaScript 是一种什么样的体验？](https://zhuanlan.zhihu.com/p/22782487)

[Front-End Developer Handbook 2017](https://frontendmasters.gitbooks.io/front-end-handbook-2017/content/)

--------------------------------------------------------------------------------

## 开发工具

- `WebStorm` / `VSCode` / `Sublime Text` / `Atom`
- `Chrome`

一些常用工具的使用方法可参考 [toolkit](https://github.com/alcat2008/toolkit)

## 版本控制 Git

- [git - 简明指南](http://www.runoob.com/manual/git-guide/)
- [常用 Git 命令清单](https://github.com/alcat2008/toolkit/blob/master/Git.md)
- [Git Community Book 中文版](http://gitbook.liuhui998.com/index.html)

## 编码规范 JavaScript

- [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
- [Airbnb React/JSX Style Guide](https://github.com/airbnb/javascript/tree/master/react)
- [Front-End Coding Guidelines](https://guide.aotu.io/index.html) 京东凹凸实验室的前端代码规范

## 调试工具

- [在 Chrome DevTools 中调试 JavaScript 入门](https://developers.google.com/web/tools/chrome-devtools/javascript/?hl=zh-cn)
- [Chrome 开发者工具](https://developers.google.com/web/tools/chrome-devtools/?hl=zh-cn)

--------------------------------------------------------------------------------

## JavaScript

- [JavaScript 教程](http://www.w3school.com.cn/js/index.asp)
- [JavaScript 秘密花园](http://bonsaiden.github.io/JavaScript-Garden/zh/)
- [跟着9张思维导图学习Javascript](http://www.jianshu.com/p/a4171444e512)
- [ECMAScript 6入门](http://es6.ruanyifeng.com/)

--------------------------------------------------------------------------------

## React - [官网](https://facebook.github.io/react/)

- [React 中文网](https://doc.react-china.org/)
- [React 入门实例教程](http://www.ruanyifeng.com/blog/2015/03/react.html)
- [React Transaction 机制](https://front-ender.cn/react/react-transaction.html)
- [ReactJS News](https://reactjsnews.com/)

### React Native - [官网](https://facebook.github.io/react-native/)

- [React Native 中文网](http://reactnative.cn/)
- [React Native Express](http://www.reactnativeexpress.com/)

### Application Architecture

- **[Flux](https://facebook.github.io/flux/)**
- [Flux 架构入门教程](http://www.ruanyifeng.com/blog/2016/01/flux.html)
- **[Redux](http://redux.js.org/)**
- [Redux 中文文档](http://cn.redux.js.org/index.html)
- [理解 Redux](https://front-ender.cn/architecture/redux.html)
- [Redux 源码分析](https://front-ender.cn/architecture/redux-source-code.html)
- [react-redux 源码分析](https://front-ender.cn/architecture/react-redux-source-code.html)
- **[dva](https://github.com/dvajs/dva)** 基于 redux、redux-saga 和 react-router 的轻量级前端框架

### Components 组件化开发思想

- [基于Decorator的组件扩展实践](https://zhuanlan.zhihu.com/p/22054582)
- [Higher-Order Components](https://reactjs.org/docs/higher-order-components.html)
- [Render Props](https://reactjs.org/docs/render-props.html)

### 其他

- [pure render](https://zhuanlan.zhihu.com/purerender) 阿里数据中台前端团队分享前端相关经验，高质量的知乎专栏
- [React 技术栈系列教程](http://www.ruanyifeng.com/blog/2016/09/react-technology-stack.html)

--------------------------------------------------------------------------------

## Vue - [官网](https://cn.vuejs.org/)

- [新手向：Vue 2.0 的建议学习顺序](https://zhuanlan.zhihu.com/p/23134551)
- [Vue 2.0——渐进式前端解决方案](http://www.infoq.com/cn/articles/vue-2-progressive-front-end-solution)
- [Vue.js 组件编码规范](https://github.com/pablohpsilva/vuejs-component-style-guide/blob/master/README-CN.md)

--------------------------------------------------------------------------------

## Test 测试

- [前端测试框架概览](https://front-ender.cn/test/front-end-test.html)
- [React 测试入门教程](http://www.ruanyifeng.com/blog/2016/02/react-testing-tutorial.html)
- [基于 React + Redux 的组件测试](https://front-ender.cn/react/react-test-component.html)

--------------------------------------------------------------------------------


# Web

### HTML

- [HTML 教程](http://www.w3school.com.cn/html/index.asp)
- [HTML5 教程](http://www.w3school.com.cn/html5/index.asp)

### CSS

- [CSS 教程](http://www.w3school.com.cn/css/index.asp)
- [CSS3 教程](http://www.w3school.com.cn/css3/index.asp)
- [学习CSS布局](http://zh.learnlayout.com/)
- [Flex 布局教程：语法篇](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)
- [CSS 编码规范](http://codeguide.bootcss.com/)
- [BEM 命名规范](http://getbem.com/naming/)

### LESS

- [LESS 一种动态样式语言](http://www.bootcss.com/p/lesscss/)
- [LESS 官网](http://lesscss.org/)
- [LESS 中文网](http://www.lesscss.net/)

### Color

- [WEB安全色](http://www.bootcss.com/p/websafecolors/)
- [Colors色彩](http://ant.design/docs/spec/colors)

--------------------------------------------------------------------------------


# 移动端

[移动端尺寸基础知识](http://colachan.com/post/3435)

[移动端高清、多屏适配方案](http://www.html-js.com/article/Mobile-terminal-H5-mobile-terminal-HD-multi-screen-adaptation-scheme%203041)

[使用Flexible实现手淘H5页面的终端适配](https://github.com/amfe/article/issues/17)

[再聊移动端页面的适配](https://www.w3cplus.com/css/vw-for-layout.html)

--------------------------------------------------------------------------------


# Data Visualization 数据可视化

[数据可视化概览](https://antv.alipay.com/zh-cn/vis/blog/vis-introduce.html)

[Canvas vs SVG](http://www.w3school.com.cn/html5/html_5_canvas_vs_svg.asp)

[WebGL 技术储备指南](http://taobaofed.org/blog/2015/12/21/webgl-handbook/)

[ECharts](http://echarts.baidu.com/)

## AntV

[AntV](https://antv.alipay.com/zh-cn/index.html) 是蚂蚁金服全新一代数据可视化解决方案，致力于提供一套简单方便、专业可靠、无限可能的数据可视化最佳实践

- [G2 可视化图形语法](https://antv.alipay.com/zh-cn/g2/3.x/index.html)
  
  一套基于可视化编码的图形语法，以数据驱动，具有高度的易用性和扩展性，用户无需关注各种繁琐的实现细节，一条语句即可构建出各种各样的可交互的统计图表

- [G6 关系数据可视化](https://antv.alipay.com/zh-cn/g6/1.x/index.html)

  关系数据可视化引擎，开发者可以基于 G6 拓展出属于自己的图分析应用或者图编辑器应用

- [F2 移动端可视化解决方案](https://antv.alipay.com/zh-cn/f2/3.x/index.html)

  专为移动端定制的一套开箱即用的可视化解决方案，具有精简、高性能、易扩展的特性。适用于对性能、大小、扩展性要求严苛的场景

## D3

[D3.js](https://d3js.org/) (Data-Driven Documents) 是基于数据操作文档的 JavaScript 库。D3 绑定数据到 DOM，根据数据操作文档，创建交互式的图表。需要注意的是，数据转换和绘制相互独立。

--------------------------------------------------------------------------------


# Design

设计体系方法论： [atomic design](http://bradfrost.com/blog/post/atomic-web-design/)，阐述了从抽象到具体的 5 个层次：

```
Atoms => Molecules => Organisms => Templates => Pages
```

[Ant Design](http://ant.design/) 一个服务于企业级产品的设计体系，基于『确定』和『自然』的设计价值观和模块化的解决方案，让设计者专注于更好的用户体验

[Material Design](https://material.google.com/) A visual language that synthesizes the classic principles of good design with the innovation of technology and science

## Components

- [Material-UI](http://www.material-ui.com/#/) React components that implement Google's Material Design
- [Ant Design Mobile](https://mobile.ant.design/) 一个基于 Preact / React / React Native 的 UI 组件库
- [Element](http://element-cn.eleme.io/#/zh-CN) 基于 Vue 2.0 的桌面端组件库
- [Vant - 移动端](https://www.youzanyun.com/zanui/vant#/zh-CN/intro) 轻量、可靠的移动端 Vue 组件库

## Solutions

- [ANT DESIGN PRO](https://pro.ant.design/index-cn) 开箱即用的中台前端/设计解决方案
- [飞冰 ICE](https://alibaba.github.io/ice)

--------------------------------------------------------------------------------


# References

[Web 前端导航](http://www.alloyteam.com/nav/)

[前端资源库](https://www.awesomes.cn/)

[Page speed optimization](https://varvy.com/pagespeed/)

[浏览器兼容性 Can I Use](http://caniuse.com/)

[Create a minimal favicon](https://favicon.io/index.html#)


## Electron - [官网](https://electron.atom.io/)

- [Electron 中文文档](https://github.com/electron/electron/tree/master/docs-translations/zh-CN)
- [Electron 深度实践总结](https://changkun.us/archives/2017/03/217/)


## TypeScript - [官网](http://www.typescriptlang.org/)

- [TypeScript中文网](http://tslang.cn/)
- [TypeScript Handbook（中文版）](https://zhongsp.gitbooks.io/typescript-handbook/content/)
- [TypeScript 的声明文件的使用与编写](https://my.oschina.net/fenying/blog/748805)
- [TypeScript Types Search](http://microsoft.github.io/TypeSearch/)
