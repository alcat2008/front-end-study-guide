---
layout: post
title: 前端题目集锦 - 选择题
categories: front-end
---

# 前端题目集锦

1. 下面代码的运行结果是

```javascript
function foo() {
  console.log(a);
}

function bar() {
  var a = 3;
  foo();
}

var a = 2;
bar();
```

A. 2
B. 3
C. undefined
D. TypeError

答案：2

2. 下面代码的运行结果是

```javascript
console.info(2 == [2]);
```

A. true
B. false

答案：A

3. 下列哪个样式定义后,内联(非块状)元素可以定义宽度和高度

A. display: inline
B. display: none
C. display: block
D. display: inherit

答案：C

block :　块对象的默认值。将对象强制作为块对象呈递，为对象之后添加新行。可以定义高度和宽度

4. css属性overflow属性定义溢出元素内容区的内容会如何处理。如果值为 scroll，不论是否需要，用户代理都会提供一种滚动机制。

A. True
B. False

答案：A

参数是scroll时候，必会出现滚动条。
参数是auto时候，子元素内容大于父元素时出现滚动条。
参数是visible时候，溢出的内容出现在父元素之外。
参数是hidden时候，溢出隐藏。

5. 新窗口打开网页，用到以下哪个值（）。

A. \_self
B. \_blank
C. \_top
D. \_parent

答案：B

如果在标签<a>中写入target属性，则浏览器会根据target的属性值去打开与其命名或名称相符的 框架<frame>或者窗口.
在target中还存在四个保留的属性值如下:
\_blank	在新窗口中打开被链接文档。
\_self	默认。在相同的框架中打开被链接文档。
\_parent	在父框架集中打开被链接文档。
\_top	在整个窗口中打开被链接文档。
framename	在指定的框架中打开被链接文档。

在html中通过<a>标签打开一个链接，通过 <a> 标签的 target 属性规定在何处打开链接文档。

6. 下面有关jquery事件的响应，描述错误的是？

A. onclick 鼠标点击某个对象
B. onfocus 元素失去焦点
C. onload 是某个页面的css js html 文档结构和图像被完成加载
D. onmousedown 某个鼠标按键被按下

答案：B

onfocus 获得焦点 onblur 失去焦点

7. flash和js通过什么类如何交互?

A. ExtensionContex
B. ExternalInterface
C. IInterpolator
D. FlexContentHolder

答案: B

Flash提供了ExternalInterface接口与JavaScript通信
两个方法：call和addCallback
作用：call让Flash调用js里的方法，addCallback是用来注册flash函数让js调用。


8. 元素的alt和title有什么异同，选出正确的说法？

A. 不同的浏览器，表现一样
B. alt和title同时设置的时候，alt作为图片的替代文字出现，title是图片的解释文字
C. alt和title同时设置的时候，title作为图片的替代文字出现，alt是图片的解释文字
D. 以上说法都不正确

答案：B
同时设置时，alt是在图片未加载完成的时候做完图片的替代文字线性，title是图片的解释文字，图片加载完成后是看不到alt的

9. 下列js可以让一个input的背景颜色变成红色的是？

A. inputElement.style.backgroundColor = 'red';
B. inputElement.backgroundColor = 'red';
C. inputElement.style.backgroundColor = '#0000';
D. inputElement.backgroundColor = '#0000';

答案: A

10. 下面有关html5标签说法错误的有？

A. <audio> 标签定义声音，比如音乐或其他音频流
B. <canvas> 比如来自一个外部的新闻提供者的一篇新的文章，或者来自 blog 的文本，或者是来自论坛的文本。亦或是来自其他外部源内容
C. <menu> 标签定义菜单列表。当希望列出表单控件时使用该标签
D. <command> 标签定义命令按钮，比如单选按钮、复选框或按钮

答案: B

<canvas> 标签定义图形，比如图表和其他图像。<canvas> 标签只是图形容器，您必须使用脚本来绘制图形。

11. 下述有关css属性position的属性值的描述，说法错误的是？

A. static：没有定位，元素出现在正常的流中
B. fixed：生成绝对定位的元素，相对于父元素进行定位
C. relative：生成相对定位的元素，相对于元素本身正常位置进行定位。
D. absolute：生成绝对定位的元素，相对于 static 定位以外的第一个祖先元素进行定位。

答案: B

fixed 生成绝对定位的元素，相对于浏览器窗口进行定位

12. 下面有关浏览器中使用js跨域获取数据的描述，说法错误的是？

A. 域名、端口相同，协议不同，属于相同的域
B. js可以使用jsonp进行跨域
C. 通过修改document.domain来跨子域
D. 使用window.name来进行跨域

答案: A

协议、域名和端口三者必须相同，才能称为相同的域。

13. 下面这个JS程序的输出是什么：

```javascript
function Foo() {
  var i = 0;
  return function() {
    console.log(i++);
  }
}

var f1 = Foo(),
  f2 = Foo();
f1();
f1();
f2();
```

A. 0 1 0
B. 0 1 2
C. 0 0 0
D. 0 0 2

答案: A

13. 请给出这段代码的运行结果（	）

```javascript
<SCRIPT LANGUAGE="JavaScript">
var bb = 1;
function aa(bb) {
    bb = 2;
    alert(bb);
};
aa(bb);
alert(bb);
</SCRIPT>
```

A. 1 1
B. 1 2
C. 2 1
D. 2 2

答案: C

ECMA中所有函数的参数都是按值传递的

14. 下面符合一个有效的javascript变量定义规则的是？

A. \_$te$t2
B. with
C. a bc
D. 2a

答案: A

JavaScript的命名规则：
1）必须以字母或者下划线开头，中间可以是.。数字、字母、下划线。
2）变量名不能包含空格、加号、减号等符号。
3）不能使用JavaScriot中的关键字。
4）JavaScript的变量名是严格区分大小写的。

15. 下面有关javascript系统方法的描述，错误的是？

A. parseFloat方法：该方法将一个字符串转换成对应的小数
B. isNaN方法：该方法用于检测参数是否为数值型，如果是，返回true，否则，反回false。
C. escape方法： 该方法返回对一个字符串编码后的结果字符串
D. eval方法：该方法将某个参数字符串作为一个JavaScript执行

答案: B

isNaN() 函数可用于判断其参数是否是 NaN，该值表示一个非法的数字。

16. 下面有关HTML的Doctype和严格模式与混杂模式的描述，错误的是？

A. 声明位于文档中的最前面，处于  标签之前。告知浏览器的解析器，用什么文档类型 规范来解析这个文档
B. 在标准模式中，浏览器根据规范呈现页面；在混杂模式中，页面以一种比较宽松的向后兼容的方式显示
C. DOCTYPE不存在或格式不正确会导致文档以标准模式呈现
D. 浏览器根据DOCTYPE是否存在以及使用的哪种DTD来选择要使用的呈现方法

答案: C

DOCTYPE不存在或格式不正确会导致文档以兼容模式呈现。

17. 下面有关JavaScript中 call和apply的描述，错误的是？

A. call与aplly都属于Function.prototype的一个方法，所以每个function实例都有call、apply属性
B. 两者传递的参数不同，call函数第一个参数都是要传入给当前对象的对象，apply不是
C. apply传入的是一个参数数组，也就是将多个参数组合成为一个数组传入
D. call传入的则是直接的参数列表。call 方法可将一个函数的对象上下文从初始的上下文改变为由 thisObj 指定的新对象。

答案: B

call 方法和 apply 方法的作用相同，他们的区别在于接收参数的方式不同。
对于 call，第一个参数是运行函数的作用域，其余参数都直接传递给函数即传递给函数的参数必须逐个列举出来。
对于 apply，第一个参数是运行函数的作用域，另一个参数是参数数组，可以是 Array 实例或 arguments 对象。


18. 下述有关border:none以及border:0的区别，描述错误的是？

A. border:none表示边框样式无
B. border:0表示边框宽度为0
C. 当定义了border:none，即隐藏了边框的显示，实际就是边框宽度为0
D. 当定义边框时，仅设置边框宽度也可以达到显示的效果

答案: C D

当定义border:none时，表示无边框样式，浏览器并不会对边框进行渲染，也就没有实际的宽度；
定义边框时，除了设置宽度外，还必须设置边框的样式才能显示出来。

19. 下面有关CSS sprites说法错误的是？

A. 允许你将一个页面涉及到的所有零星图片都包含到一张大图中去
B. 利用CSS的“background-image”，“background-repeat”，“background-position”的组合进行背景定位
C. CSS Sprites虽然增加了总的图片的字节，但是很好地减少网页的http请求，从而大大的提高页面的性能
D. CSS Sprites整理起来更为方便，同一个按钮不同状态的图片也不需要一个个切割出来并个别命名

答案: C

CSS Sprites能减少图片的字节。

20. 下面列出的浏览器，无webkit内核的是（）

A. chrome
B. Safari
C. 搜狗浏览器
D. firefox

答案: D

Firefox便是使用的Gecko 内核，微软的IE系列则使用的是Trident内核。

21. 要在10秒后调用checkState，下列哪个是正确的

A. window.setTimeout(checkState, 10);
B. window.setTimeout(checkState, 10000);
C. window.setTimeout(checkState(), 10);
D. window.setTimeout(checkState(), 10000);

答案：B

checkState 加了圆括弧相当于函数表达式，会立即执行，执行的结果作为返回值传递给 setTimeout。

22. 下面哪个不属于Promise的状态？

A. Unfulfilled
B. Rejected
C. Resolved
D. Pause

答案：D

promise 模式在任何时刻都处于以下三种状态之一：未完成（unfulfilled）、已完成（resolved）和拒绝（rejected）。

23. 把鼠标移到按钮并点击时，会产生一串什么样的事件？

A. active hove focus
B. foucs hove active
C. hover active foucus
D. hover focus active

答案：D

CSS伪类用于向某些选择器添加特殊的效果。
  :active 向被激活的元素添加样式。
  :focus 向拥有键盘输入焦点的元素添加样式。
  :hover 当鼠标悬浮在元素上方时，向元素添加样式。
  :link 向未被访问的链接添加样式。
  :visited 向已被访问的链接添加样式。


24. 一台刚刚接入互联网的WEB服务器第一次被访问到时，不同协议的发生顺序是下面中的____。

A. ARP -> DNS -> HTTP
B. ARP -> HTTP -> DNS
C. DNS -> HTTP -> ARP
D. DNS -> ARP -> HTTP
E. HTTP -> ARP -> DNS
F. HTTP -> DNS -> ARP

答案：A

1、当给WEB服务器接上网线的时候，它会自动发送一条ARP信息，使得接入网关能找的到它；
网关上会形成一条类似：2c 96 1e 3c 3e 9b - 192.168.1.123的MAC地址到IP地址的映射记录。
2、当第一个用户使用域名访问WEB服务器的时候，首先要进行一次DNS查询
3、最后才是http协议

25. 下列哪个IP地址可以分配给一台计算机?

A. 256.1.3.4
B. 197.3.11.0
C. 199.5.89
D. 11.15.33.235

答案：D

A中256不合法，B代表一个网段，C代表了一个直接相连的网络，D作为一个A类地址，是可以分配给一台计算机的。

26. 下面关于虚拟局域网VLAN的叙述错误的是()

A. VLAN是由局域网网段构成的与物理位置无关的逻辑组
B. 利用以太网交换机可以很方便地实现VLAN
C. 每一个VLAN的工作站可处在不同的局域网中
D. 不同VLAN内的用户可以相互之间直接通信
E. vLAN可以强化网络安全和网络管理
F. VLAN能灵活控制广播活动

答案：D

27. 关于HTML语义化，以下哪个说法是正确的？

A. 语义化的HTML有利于机器的阅读，如PDA手持设备、搜索引擎爬虫；但不利于人的阅读
B. Table 属于过时的标签，遇到数据列表时，需尽量使用 div 来模拟表格
C. 语义化是HTML5带来的新概念，此前版本的HTML无法做到语义化
D. Header、article、address都属于语义化明确的标签

答案：D

28. 以下哪种http状态下,浏览器会产生两次http请求?()

A. 304
B. 404
C. 302
D. 400

答案：C

302暂时重定向

29. 若路由器接收的ip报文的目的地址不是路由器的接口ip地址，并且未匹配的路由项，则采取的策略是（）。

A. 丢掉该分组
B. 将该分组分片
C. 转发该分组
D. 将分组转发或分片
E. 将分组保留存储
F. 以上都有可能

答案：A

30. 关于HTTP协议，下面哪个说法是正确的？

A. HTTP协议是有状态协议。
B. 以下是一个Http链接的response 的响应头： GET /xxx/xxx/js/lib/test.js HTTP/1.1 Host: 127.0.0.1 Connection: keep-alive Pragma: no-cache Cache-Control: no-cache Accept: */*
C. RESTful 接口中，利用HTTP协议的method字段来描述要对资源操作的方式，比如GET表示获取资源，POST表示新增一个资源，PUT表示更新资源,DELETE 表示删除资源等等。
D. 一个HTTP请求返回的HTTP状态码中，304表示临时重定向。

答案：C

31. 下面代码的运行结果是

```javascript
var a = 2;
function add(a, b) {
  return
    a + b;
}
console.log(add(1, 2));
```

A. 3
B. 4
C. undefined
D. TypeError

答案：C


32. 下面代码的运行结果是

```javascript
function foo(){}
delete foo.length;
console.log(typeof foo.length);
```

A. number
B. undefined
C. object
D. TypeError

答案：A
