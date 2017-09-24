#### 1. 字符串转 Buffer

```js
new Buffer(str, [encoding]) // encoding 默认 utf-8

// 写入
// offset 起始位置
// length 写入的长度
buf.write(string, [offset], [length], [encoding])
```

#### 2. Buffer 转字符串

```js
buf.toString([encoding], [start], [end])
```

#### 3. Buffer 不支持的转码类型

```js
Buffer.isEncoding(encoding)
```



