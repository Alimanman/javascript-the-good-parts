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

- 通过对象字面量创建的对象都连接到Object.prototype。

- 可以选择某个对象作为它的原型。



