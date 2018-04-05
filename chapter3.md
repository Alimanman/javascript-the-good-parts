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