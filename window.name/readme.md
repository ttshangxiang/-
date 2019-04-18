## 使用npm install http-server -g安装简易服务器

原理：window.name在设置好以后，就算修改location.href，window.name也不会发生改变。

1，创建跨域iframe，在iframe里获取数据后，保存到window.name。
2，将跨域iframe的src转化为同源的iframe。
3，原窗口使用iframe.contentWindow.name可以获取数据。