# learning
learn everything i interested in

var ，let ， const 的区别：

不存在变量提升

var 命令会发生变量提升现象，即变量可以在声明之前使用，值为undefined。
let 和 const 则没有变量声明提升的功能，必须要先声明才能使用

不允许重复声明

var命令能重复声明，后者覆盖前者
let 和 const不允许在相同作用域内，重复声明同一个变量

作用域

var 的作用域是以函数为界限
let 和 const 的作用域是块作用域，块级作用域指 { } 内的范围
var 可以定义全局变量和局部变量，let 和 const 只能定义局部变量
const 的声明的常量不能被修改，但对于引用类型来说，堆内存中的值是可以被改变的。

变量作为全局属性

定义的变量会作为window对象的属性，let不会


