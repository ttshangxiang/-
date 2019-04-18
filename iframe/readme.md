## 使用npm install http-server -g安装简易服务器

iframe跨域，利用iframe同源可访问内容原理

1，写一个全局方法getData，用来获取数据。
2，内嵌跨域iframe，在此iframe内获取目标数据。
3，改变内嵌跨域iframe的href为一个同源URL，并将数据附在src上。
4，同源iframe可以使用window.top.getData('数据')，来将数据传回。
