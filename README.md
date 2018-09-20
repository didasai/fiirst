1、作用域public,private,protected,以及不写时的区别
答：区别如下：
作用域           当前类       同一package  子孙类       其他package
public            √              √          √             √
protected         √              √          √             ×
friendly          √              √          ×             ×
private           √              ×          ×             ×
不写时默认为friendly
