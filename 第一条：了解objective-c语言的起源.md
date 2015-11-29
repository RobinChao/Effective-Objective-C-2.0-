# 第一条：了解Objective-C语言的起源

Objective-C 语言是通过一套全新的语法，在C语言的基础上添加了面向对象的特性。

Objective-C 语言与C++、Java等面向对象的语言类似，但是Objective-C语言有很多范式和模板。
Objective-C 语言使用了"消息结构"（messageing structure）而非"函数调用"（function calling)。Objective-C 语言是由Smalltalk语言演化而来，而Smalltalk语言是消息性语言的鼻祖。而消息和函数调用之间的关键性区别在于：

* 使用消息结构的语言，其运行时所应执行的代码由运行环形来决定
* 使用函数杜鳌用的语言，其运行时所应执行的代码由编译器决定

Objective-C 语言的重要工作都由“运行时组件”（runtime component）而非编译器来完成。

Objective-C 语言是C语言的“超集”（superset），所以C语言的所有功能在编写Objective-C 代码时依然适用。

Objective-C 语言的内存管理是由其“引用计数”（reference counting）机制来管理。  
  
Objective-C 语言中的指针式用来指示对象的。  
  
Objective-C 语言使用动态绑定的消息结构，也就是说，Objective-C 语言在运行时才检查对象类型。  当接收一条消息后，究竟应执行何种代码，由运行时环境而非编译器来决定。
  


