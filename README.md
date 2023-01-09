# Get Started

- 首先需要准备一个WebSocket服务  
 First you need to prepare a WebSocket service  
- 在虚幻商城搜索WebSocketClient，找到插件，点击安装，支持虚幻引擎4.27及以上版本；  
 Search for WebSocketClient in Unreal Mall, find the plug-in, click to install, it supports Unreal Engine 4.27 and above;
- 将WebSocketServerClient内容/BluePrint下的BP_WebSocketClientActor拖入场景中，在细节面板中的Server URl填入WS地址（例如：ws://127.0.0.1:9091)  
 Drag the BP_WebSocketClientActor under WebSocketServerClient content/BluePrint into the scene, and fill in the WS address in the Server URL in the details panel (for example: ws://127.0.0.1:9091)
- WebSocketServerClient内容/BluePrint下的BP_WebSocketController提供了连接、发送消息、接收消息等蓝图用法，可以参考  
 BP_WebSocketController under WebSocketServerClient content/BluePrint provides blueprint usages such as connection, sending messages, receiving messages, etc., you can refer to
- 点击运行，可以尝试和WebSocket Server通信了  
 Click to run, you can try to communicate with WebSocket Server

# Simple description

![Simple description](./Resources/BlueprintDemo.png)

# Featured Demos

1.以Actor连接WebSocket服务器，方便在云端渲染架构下于你的后台进行通信

Use Actor to connect to the WebSocket server to facilitate communication in your background under the cloud rendering architecture

2.支持自定义IP、端口

Support custom IP, port

3.提供蓝图调用，包括接收消息事件、连接事件、发送消息事件

Provide blueprint calls, including receiving message events, connection events, and sending message events

4.提供简易的JSON序列化，提供Brief、Command、Type三个字段，便于建立自己的指令集

Provide simple JSON serialization, provide Brief, Command, Type three fields, easy to build your own instruction set

5.对于打包后的程序，提供命令行方式设置IP和端口 -ws ws://127.0.0.1:9091

For the packaged program, provide command line mode to set IP and port -ws ws://127.0.0.1:9091
