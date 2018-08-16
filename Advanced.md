# 前端学习指南 - 进阶篇之 “道”

本文重点关注技术背后的原理、架构思考、编程方法论等方面。会搜集看到的一些好文章、讨论等。如果您有推荐，请提 PR ，谢谢！


--------------------------------------------------------------------------------

# Architecture 架构

[系统设计黄金法则：简单之美](http://blog.sciencenet.cn/home.php?mod=space&uid=414166&do=blog&id=562616)

[Arale 背后的一些设计理念](https://github.com/lifesinger/blog/issues/106)

[我理解的阿里无线前端“架构”](https://github.com/amfe/article/issues/3)

[理想的应用框架](http://www.cnblogs.com/sskyy/p/4592353.html)

[Web 研发模式演变](https://github.com/lifesinger/blog/issues/184)

[单页应用的数据流方案探索](https://zhuanlan.zhihu.com/p/26426054)


## 服务化

[页面可视化搭建工具前生今世](https://zhuanlan.zhihu.com/p/37171897)

[前端服务化——页面搭建工具的死与生](http://www.cnblogs.com/sskyy/p/6496287.html)

[前端即服务-通向零成本开发之路](https://os.alipayobjects.com/rmsportal/sJqXvOtwePsVWGNIwlas.pdf)

[美团外卖前端可视化界面组装平台 —— 乐高](https://tech.meituan.com/waimai_lego.html)


## 工程化

[fouber 的博客](https://github.com/fouber/blog)

[个人理解的前端工程化](https://front-ender.cn/architecture/front-end-engineering.html)


## 组件化和模块化

[2015前端组件化框架之路](https://github.com/xufei/blog/issues/19)

[前端工程与模块化框架](http://div.io/topic/439)

[关于前端开发中“模块”和“组件”概念的思考](https://github.com/hax/hax.github.com/issues/21)

[重新设计 React 组件库](https://zhuanlan.zhihu.com/p/24207409)


--------------------------------------------------------------------------------

# Design Pattern 设计模式

[JavaScript设计模式：单例模式](http://www.zcfy.cc/article/javascript-design-patterns-the-singleton-918.html)


--------------------------------------------------------------------------------

# Programming Methodology 编程方法论

[Overcoming Intuition in Programming](https://amasad.me/intuition)

[程序观点下的线性代数](http://www.cnblogs.com/weidagang2046/p/linear-algebra-from-programming-perspective.html)

## Defensive programming 防御性编程/安全编程

> 基本规则：保护程序免遭非法输入数据的破坏。

- 提供默认值
- 使用 propTypes/type 属性校验类型
- 使用 props 之前先检查该 prop 是否存在

## 数据流

[前端数据流哲学](https://zhuanlan.zhihu.com/p/33382396?group_id=941233109623169024)

## Monads

[Functors, Applicatives, And Monads In Pictures](http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html)

中文版

[图解 Monad](http://www.ruanyifeng.com/blog/2015/07/monad.html)

## Functional Programming 函数式编程

[mostly-adequate-guide/details](https://drboolean.gitbooks.io/mostly-adequate-guide/content/)

中文版

[JS函数式编程指南](https://www.gitbook.com/book/llh911001/mostly-adequate-guide-chinese/details)

## React Basic Theoretical Concepts

[React - Basic Theoretical Concepts](https://github.com/reactjs/react-basic)

中文版

[React 设计思想](https://github.com/react-guide/react-basic)

[React的设计哲学 - 简单之美](http://www.infoq.com/cn/articles/react-art-of-simplity)


--------------------------------------------------------------------------------

# Principle 原理

[How Browsers Work: Behind the scenes of modern web browsers](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)

[What-happens-when](https://github.com/skyline75489/what-happens-when-zh_CN)

[JavaScript的 AST 抽象语法树与语法解析](http://wwsun.github.io/posts/javascript-ast-tutorial.html)


--------------------------------------------------------------------------------

# Performance 性能

[浏览器前端优化](http://jinlong.github.io/2017/05/08/optimising-the-front-end-for-the-browser/)

[7 天打造前端性能监控系统](http://fex.baidu.com/blog/2014/05/build-performance-monitor-in-7-days/)

[14 Rules for Faster-Loading Web Sites](http://stevesouders.com/hpws/rules.php)

[JavaScript 启动性能瓶颈分析与解决方案](http://mp.weixin.qq.com/s?__biz=MzIwNjQwMzUwMQ==&mid=2247484987&idx=1&sn=7f20da20bc6baed62ca8ff115209942b)

## BigPipe

[BigPipe: Pipelining web pages for high performance](https://www.facebook.com/note.php?note_id=389414033919)

[Facebook让网站速度提升一倍的BigPipe技术分析](http://limu.iteye.com/blog/765173)
