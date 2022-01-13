# ST-CryptoServer
#### 启动命令

```shell
wget https://github.com/C3Pool/ST-CryptoServer/releases/download/v1.0.5/StarMap-CryptoTool.gz
tar zxvf StarMap-CryptoTool.gz
chmod +x StarMap-CryptoTool
./StarMap-CryptoTool -h 0.0.0.0 -p 18681 -s tcp.starmap.asia -b 43321 -c 8898
```

##### 参数解析：

- -h: 绑定地址，允许所有访问 使用0.0.0.0(默认)。
- -p: 本地监听端口(默认18681)。
- -s: 远程矿池地址。
- -b: 远程矿池端口。
- -c: 网页监控端口(默认8898)。

##### 注意：

- 本工具仅支持明文TCP连接矿池，暂不支持SSL连接。

- 如连接失败，请检查服务器提供商控制台，是否已在安全组中开启对应端口

- 工具暂未处理内核抽水连接

