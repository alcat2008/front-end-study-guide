---
layout: post
title: 前端题目集锦 - 编程题
categories: front-end
---

1. 实现一个函数clone，可以对JavaScript中的5种主要的数据类型（包括Number、String、Object、Array、Boolean）进行值复制

- 考察点1：对于基本数据类型和引用数据类型在内存中存放的是值还是指针这一区别是否清楚
- 考察点2：是否知道如何判断一个变量是什么类型的
- 考察点3：递归算法的设计

```javascript
// 方法一：
Object.prototype.clone = function() {
  var o = this.constructor === Array ? [] : {};
  for (var e in this) {
    o[e] = typeof this[e] === "object" ? this[e].clone() : this[e];
  }
  return o;
}

// 方法二：
/**
 * 克隆一个对象
 * @param Obj
 * @returns
 */
function clone(Obj) {
  var buf;
  if (Obj instanceof Array) {
    buf = [];                    //创建一个空的数组
    var i = Obj.length;
    while (i--) {
      buf[i] = clone(Obj[i]);
    }
    return buf;
  } else if (Obj instanceof Object) {
    buf = {};                   //创建一个空对象
    for (var k in Obj) {           //为这个对象添加新的属性
      buf[k] = clone(Obj[k]);
    }
    return buf;
  } else {                         //普通变量直接赋值
    return Obj;
  }
}
```

2. 如何消除一个数组里面重复的元素？

```javascript
myArray.filter(function(elem, pos, self){
  return self.indexOf(elem) == pos;
});
```

3. 实现快速排序（Quicksort）算法

"快速排序"的思想很简单，整个排序过程只需要三步：

```shell
  1) 在数据集之中，选择一个元素作为"基准"（pivot）。
  2) 所有小于"基准"的元素，都移到"基准"的左边；所有大于"基准"的元素，都移到"基准"的右边。
  3) 对"基准"左边和右边的两个子集，不断重复第一步和第二步，直到所有子集只剩下一个元素为止。
```

实现代码：

```javascript
var quickSort = function(arr) {
　　if (arr.length <= 1) { return arr; }
　　var pivotIndex = Math.floor(arr.length / 2);
　　var pivot = arr.splice(pivotIndex, 1)[0];
　　var left = [];
　　var right = [];
　　for (var i = 0; i < arr.length; i++){
　　　　if (arr[i] < pivot) {
　　　　　　left.push(arr[i]);
　　　　} else {
　　　　　　right.push(arr[i]);
　　　　}
　　}
　　return quickSort(left).concat([pivot], quickSort(right));
};
```

4. 分别定义构造函数 Parent 和 Child，并利用原型链使得 Child 继承 Parent 的所有属性和方法。

思路：**利用构造函数继承实例属性，利用原型链继承原型属性和方法**。

```javascript
// 返回一个继承自原型对象 p 的属性的新对象
function inherit(p) {
  if (p == null) throw TypeError();  // p 是一个对象，但不能是 null
  if (Object.create) return Object.create(p); // 若 Object.create 存在，则直接使用它

  var t = typeof p;
  if (t != "object" && t != "function") throw TypeError();
  function F() {}; // 定义空构造函数
  F.prototype = p; // 将其原型属性设置为 p
  return new F(); // 使用 f() 创建 p 的继承对象
}

function Parent() {}
function Child() {}

Child.prototype = inherit(Parent.prototype);
Child.prototype.constructor = Child;
```

5. 实现 isJSON(str) 函数，判断 str 是否为有效的 JSON 字符串

```javascript
function isJSON(str) {
  try {
    const obj = JSON.parse(str);
    return !!obj && typeof obj === 'object';
  } catch (e) { /* ignore */ }
  return false;
}
```

6. 谈一谈你所接触过的前端库或者框架（jQuery/React/Angular/Vue...），并谈一谈对它的理解。
