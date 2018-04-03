# 语法
---

#### 注释

- 避免使用`/* */`，建议使用`//`。

#### 标识符 Names

- 字母开头，其后可以添加字母、数字或者下划线。
  
  其实可以已_和$开头，本书作者不推荐。。。

- 标识符被用于语句、变量、参数、属性名、运算符和标记。

#### 数字

- JavaScript中只有一种数字类型：number。
  
  没有往浮点和整数细分。
  `1 == 1.0 //true`

- NaN(Not a Number)表示一个不能产生正常结果的运算结果。NaN不等于任何，包括自己。
  `NaN == NaN //false`
  
#### 字符串

- 转义字符用来把正常情况下不被允许的字符插入到字符串中。

#### 语句 Statements

- var用在函数内，定义的是这个函数的私有变量。

- JavaScript中的`{}`代码块无作用域功能。

- switch、while、for和do有一个前置标签label，可以配合break使用。

- if语句视为假的值
  false、null、undefind、空字符串、0、NaN
  
- for in枚举一个对象的所有属性名。

- do while 和 while的区别在于，前者不管什么条件至少会实行一次。

- return默认返回值是undefined。

- break退出一个循环，可指定一个label

#### 表达式 Expressions
  


