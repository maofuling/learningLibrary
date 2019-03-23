##  this用法
this是一个执行上下文相关的特殊对象，可以称为上下文对象（指明执行上下文是在那个上下文中触发的对象），同时任何对象均可作为上下文this的值，他不是变量对象的属性。


this不会参与标识符解析的过程，即在代码访问this时，他的值是直接从执行上下文中获取的，不需要任何作用域链查找，this值只在进入上下文时进行一次确定。ECMAScript里，由于他并不是变量且不存在变量对象，不能给this赋新值。