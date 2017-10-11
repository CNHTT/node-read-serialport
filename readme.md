# readme
本程序为nodejs的web端口调试工具. 目前还存在一些小问题,不过大致上来说流程已经能够跑通了

# 要求

1.  node > 7 <8  编译在v7.9.0
2.  win64系统 (mac未测试)

# 启动

```
npm install
node app.js
```
打开浏览器访问`http://127.0.0.1:3050`

# 使用说明
首先选择`port` 比如 COM3 然后选择`baudRate` 接着点击 `open port`
接着就可以去调试了. 整个程序并不难,代码都比较少,因为赶工期所以就没做优化了. 目前还存在一些小问题.
如果出现bug 或者报错 先刷新页面 然后重启nodejs服务即可.

# todolist

[x] socket.io调试
[x] 自定义码率和端口调试
[x] 特殊设备如果返回图片则前端渲染图片
[]  某些情况下还会出现bug