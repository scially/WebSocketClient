# Get Started

- 首先需要准备一个WebSocket服务
- 在虚幻商城搜索WebSocketClient，找到插件，点击安装，支持虚幻引擎4.27及以上版本；
- 将WebSocketServerClient内容/BluePrint下的BP_WebSocketClientActor拖入场景中，在细节面板中的Server URl填入WS地址（例如：ws://127.0.0.1:9091)
- WebSocketServerClient内容/BluePrint下的BP_WebSocketController提供了连接、发送消息、接收消息等蓝图用法，可以参考
- 点击运行，可以尝试和WebSocket Server通信了

# Simple description

![Simple description](./Resources/BlueprintDemo.png)

# Featured Demos

- 以Actor连接WebSocket服务器，方便在云端渲染架构下于你的后台进行通信
- 支持自定义IP、端口
- 提供蓝图调用，包括接收消息事件、连接事件、发送消息事件
- 提供简易的JSON序列化，提供Brief、Command、Type三个字段，便于建立自己的指令集
- 对于打包后的程序，提供命令行方式设置IP和端口`-ws ws://127.0.0.1:9091'
