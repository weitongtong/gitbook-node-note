一个最基本的 server ：

```js
var http = require('http')
http.createServer(function(req, res) {
    res.writeHead(200, { 'Content-Type': 'text/plain' })
    res.end('Hello, World\n')
}).listen(3000, 127.0.0.1)
```

具体的Web应用还需要：

* 请求方法的判断。
* URL的路径解析。
* URL中查询字符串解析。
* Cookie的解析。
* Basic认证。
* 表单数据的解析。
* 任意格式文件的上传处理。
* 。。。

##### 1. 请求方法

##### 2. 路径解析

##### 3. 查询字符串

##### 4. Cookie







