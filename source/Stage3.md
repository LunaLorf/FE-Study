## Level 3 渐入佳境
## 任务1 JavaScrit基础
###任务目的 

掌握JavaScript基础知识，能够使用JavaScript编写一些复杂度不大的交互功能

### 学习内容

+ JS语言基础
    + JS介绍：`html、css --> js`、`hello  world`、js特性,`js&DOM`、js历史
    + JS调试：`alert`、`console`、展示chrome,ff,ie   调试器界面、以Chrome为例子，详细展示、展示面板作用、查找要调试的文件、设置断点，debugger、展示4个按钮，并展示响应的堆栈变化，watch
    + 基本语法：标识符、变量、直接量、关键字和保留字、语句、区分大小写、注释
    + 基本类型：`Number（Interger, Float, NaN,Infinity）`、`String("",’’)`、`Boolean(true,false)`、`undefined`(什么情况下为`undefined`)、null、Object({})、原始类型和引用类型的区别、typeof
    + 运算符与表达式：	表达式、运算符、一元操作符(`++,--, +,-`)、算术运算(`+、-、*、/、%`)、关系运算`(>、<、== 、!=、>=、<=、===、!==)`、逻辑运算`(！、&&、 ||)`、位运算`(&、|、^、~、<<、>>,>>>)`、赋值运算(=)、条件运算(?:)、逗号运算(,)、对象运算符`(new delete . [] instanceof)`、运算符的优先级
    + 语句：	语句、条件（`if`,`switch`）、循环（`for/for in/ while/ do-while`） `lable break continue`、异常 (`try catch finally`)、`with`、`label`
    + 数值:	Math`（abs、round、ceil、floor、max、min、random、其他`）、`parseInt、parseFloat、Number、NaN、toFixed`
    + 字符串:定义、`length`、`charAt（下标）`、`indexOf`、`lastIndexOf`、`search、match、replace、substring、slice、substr、split、toLowerCase、toUpperCase`、连接、转字符串（+、String()）、转义
    + 对象:	定义、创建（new、直接量）、属性、方法、constructor、toString、valueOf、hasOwnproperty
    + 数组:定义、创建（new、直接量）、`length`、`indexOf`、`forEach`、【（`reverse`、`sort`）、（`push`、`unshift`）、（`shift`、`pop`）、`splice`】、`【slice、concat、join、reduce】`
    + 函数:函数定义(函数声明、函数表达式、函数参数、return)、函数调用、arguments、作用域、对象方法、构造函数、function.prototype
    + Date:`new Date()`,`Date.getXXXX()`,格式化, `Date.setXXX()`,求天数, `Date.getTime()`
    + RegExp:字符类、元字符、量词、多选分支、转义、捕获、匹配模式
    + JSON:定义，`JSON.parse()`,`JSON.stringify`
+ JS进阶
    + 类型进阶： 数识别应用场景（字符串和数组的例子）、类型识别方法：`typeof`，`constructor`,`Object.prototype.toString`,instanceof和其他（Array.isArray, isNaN)、类型转换（所有的方法+隐式转换）
    + 函数进阶：函数定义（函数声明、函数表达式、`new Function`）、`arguments（callee、转数组）`、`apply`、`call`、`bind`、高阶函数（AOP、curry、记忆函数）
    + 原型：原型（概念）、构造函数、原型链（原型链,原型链查找,原型链修改,原型链删除,`Function.prototype`,`Object.prototype`）、原型继承
    + 变量作用域：	动态作用域和静态作用域，词法环境（函数作用域），作用域链，`with/catch`
    + 闭包：闭包举例、闭包原理、闭包应用
    + 面向对象：JS面向对象
    
### 参考资料

+ [妙味课堂-精通JavaScript开发][1]
+ 《JavaScript高级程序设计》前1-13章
+ [慕课网JavaScript入门篇][2]
+ [慕课网JavaScript进阶篇][3]
+ [MDN][4]

### 练习

1. 下拉菜单
2. Tab选项卡切换
3. 倒计时效果
4. 轮播图
5. 一个简易JS计算器
    + 使用HTML/CSS/Javascript制作一个简单的计算器，要求：具备两个数字（包括小数）的加减乘除，一个数字的求百分比功能；各种颜色和字体等样式都按照你的个人喜好来设计。[参考图][http://ww1.sinaimg.cn/large/74990035gw1edwkx6v8hjj208h08j3ym.jpg]
6. 利用Ajax做一个天气预报  
要求:
    + 给你们一个接口，返回的是近5天的重庆天气格式为JSON
    + 写一个天气预报的页面
    + 根据所获得的数据做一个5天天气预报
    + 要轮播效果
    + 请求接口用ajax
    [API地址][http://openweathermap.org/data/2.5/forecast/daily?id=1814906&appid=b1b15e88fa797225412429c1c50c122a]
    PS：尽量好看点
 

##任务2  规范（JS）	杰
##任务3   谷歌调试（JS）	磊
##任务4 DOM/BOM
### BOM （Browser Object Model，浏览器对象模型）
- window对象：表示浏览器打开的窗口，包括获取焦点、改变滚动条、设置定时器等等。
- location对象：可对当前页面的URL进行操作，如：导航到新的页面、获取URL信息等。
- navigation对象：包含浏览器信息。如：获取浏览器名称、版本信息、操作系统平台信息等等。
- screen对象：包含屏幕信息。如：获取屏幕高度、宽度等等。
- history对象：可对当前页的浏览历史进行操作，如：前进、后退等。  
**作业：**  
	阅读《JavaScript高级程序设计》第8章`BOM`，标注或分类整理常用的浏览器API，最好写到博客或相关文档内，方便以后查阅使用。  
	可以参考慕课网JavaScript进阶篇第8章，操作实践。  
**参考资料：**  
	[慕课网 JavaScript进阶篇第8章](http://www.imooc.com/learn/10)
##任务5 AJAX/HTTP/JSON		杰
##任务6 JQuery	磊
##任务7 js实战	晶
##任务8 运动/动画	晶
##任务9 正则	磊
##任务10 RequireJs	磊


  [1]: http://pan.baidu.com/s/1pLH6t7t
  [2]: http://www.imooc.com/view/36
  [3]: http://www.imooc.com/view/10
  [4]: https://developer.mozilla.org/en-US/docs/Web/JavaScript
