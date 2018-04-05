# 对象 Objects
---

#### 对象字面量 Object Literals

包围在一对花括号中的零个或者多个“名/值”对，属性名不强制引号。
对象可以嵌套。

```
var empty_object = {};

var stooge = {
    'first_name': 'Jerry',
    'last_name': 'Huang'
}

var flight = {
    ariline: 'Oceanic',
    departure: {
        time: '2018-04-04',
        city: 'ShangHai'
    }
}
```

索引和更新

```
stooge['first_name'];
stooge.first_name;

stooge['first_name'] = 'Tom';
stooge.first_name = 'Tom';

```

#### 原型 Prototype

- 每个对象都连接到一个原型对象。

- 对象字面量创建的对象都**连接**到Object.prototype。

- 可以选择某个对象作为它的原型。

 - 创建的每个函数天生都自带着一个prototype。

 - 当对某个对象作出改变时，原型不会改变。

 - 原型添加一个新属性，基于该原型创建的对象也可见。
 
- hasOwnProperty检测是否对象独有属性，不会检测原型链。




