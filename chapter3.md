# 函数 Functions
---

#### 函数对象

- JavaScript中函数就是对象。

- 函数对象**连接**到Function.prototype。

- 每个函数对象有一个prototype。它的值是一个拥有constructor属性且其值为该函数的对象。
```
myfun == myfun.prototype.constructor //true
```

#### 函数字面量

```
var add = function(){};
```
匿名函数传递给变量

#### 方法调用模式

- 当一个函数保存为一个对象的属性，我们称它为方法。

- this被绑定到该对象，方法可以使用this访问自己所属的对象。

#### 函数调用模式

- this默认被绑定到全局对象。
````
var that = this; //解决办法
````

使用es6的箭头函数也可以解决这个问题。

#### 构造器调用模式

- new前缀调用被称作为构造器函数（不推荐这种形式的构造器函数，后续介绍更好的方式

- 建议首字母大写格式命名变量名。

- 每个函数对象都有一个prototype。通过new来调用，会创造一个连接到该函数prototype的新对象，this绑定在新对象上。

- 在prototype添加所有实例化可用的公共属性和方法

#### Apply调用模式

- 函数也拥有方法。

#### Return

- 一个函数总会返回一个值，没有指定则返回undefined。

- 如果函数调用前面加了new，返回的是this。即该新对象。

#### 递归 Recursion

递归函数就是会直接或间接调用自身的一种函数。













