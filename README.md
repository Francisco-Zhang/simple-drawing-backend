# simple-drawing-backend

此项目是使用 GO 语言编写的简单白板（涂鸦）服务端功能。 所使用的通信协议是 WebSocket，因此所有的用户都将实时看到彼此的绘制路径。其次，用户还可以为画笔设置颜色等。

### Running

Buld and run the server.

```
$ go build -o server && ./server
```

Open client/index.html in your browser.

![效果截图](snap.gif)
