### 1. 作用域链 
当查找变量的时候， 会先从当前上下文的变量对象中查找，如果没有找到， 会从父级执行上下文的变量对象中查找， 一直查找到全局上下文的变量对象， 也就是全局对象，这样有多个执行上下文构成的链表就叫作用域链
