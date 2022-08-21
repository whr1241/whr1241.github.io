---
layout:    post
title:      "JavaScript总结"
subtitle:   " \"阶段学习总结\""
date:       2022-08-17
author:     "Oran"
header-img: "assets/imgs/post-bg-2015.jpg"
catalog: true
published: true
tags:
    - 前端
    - JavaScript
---
// 这是注释
/ \*也是注释 \*/ 

基础分为三个部分：
    1.ECMAScript语法标准
    2.DOM文档对象模型，来操作页面元素的API
    3.BOM浏览器对象模型，操作浏览器部分功能的API

有三种引入方式:行内式、内嵌式、外联式；和CSS的三种引入方式类似又有不同。

JS 对换行、缩进、空格不敏感。每一条语句要以分号结尾。 严格区分大小写。

ES6 提出了四大组件：Promise、类、模块、生成器/迭代器。

常量：
1.数字常量（数值常量）
2.字符串常量
3.布尔常量
4.自定义常量（ES6中新增的语法）：`const 常量名称 = 常量取值;`

变量的定义/声明：
1.var name;  （ES5）
2.const name;  （ES6）
3.let age;  （ES6）
变量的赋值：可以分开：var num; num = 996; 也可以合并：var num = 996;

关键字，就是有特殊功能的单词：var、
标识符，就是我们自主命名的：变量名、函数名、属性名、参数名
保留字，就是预留的“关键字”

JS 中一共有八种数据类型：
1.基本数据类型（值类型）：String 字符串、Number 数值、BigInt 大型数值、Boolean 布尔值、Null 空值、Undefined 未定义、Symbol。
2.引用数据类型（引用类型）：Object 对象。
注意：内置对象 Function、Array、Date、RegExp、Error 等都是属于 Object 类型。也就是说，除了那七种基本数据类型之外，其他的，都称之为 Object 类型。

JS 中，所有的变量都是保存在栈内存中的；对象是保存到堆内存中的。
对象的值是保存在堆内存中的，而对象的引用（即变量）是保存在栈内存中的。

JS 语言中，既有 null，又有 undefined：
Null：空对象，变量初始化时将其设置为 null
undefined：未定义类型，声明了一个变量，但没有赋值
10 + null 结果为 10
10 + undefined 结果为 NaN

三元运算符：`条件表达式 ? 语句1 : 语句2;`

传值与传址：

DOM：文档对象模型（Document object Model），用来操作网页上的元素的API。比如让盒子移动、变色、轮播图等。DOM就是由节点组成的。

BOM：浏览器对象模型（Browser Object Model），操作浏览器部分功能的API。比如让浏览器自动滚动。

