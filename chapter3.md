# 函数 Functions
---

#### 函数对象

- JavaScript中函数就是对象。

- 函数对象**连接**到Function.prototype。

- 每个函数对象有一个prototype。它的值是一个拥有constructor属性且其值为该函数的对象。
```
myfun == myfun.prototype.constructor //true
```