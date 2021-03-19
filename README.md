# moosocks


**服务端**
在服务器端中启动路径，打开。/cmd/server/，运行`go run main.go`
服务端命令参数有三个：
```
  -local string #设置服务器对外端口
    	Input server listen address(Default 8888): (default ":18888")
  -passwd string #设置服务器对外密码
    	Input server proxy password: (default "123456")
  -type string #设置加密类型
    	Input encryption type: (default "random")
```

**客户端**
在客户端中启动路径，打开。/cmd/client/，运行`go run main.go`
服务端命令参数有四个：

```
  -local string #设置客户端的本地转发端口
        Input server listen address(Default 8888): (default ":8888")
  -passwd string #设置服务器的密码
        Input server proxy password: (default "123456")
  -server string #设置服务器ip地址和端口
        Input server listen address, for example: 16.158.6.16:18181
  -type string #设置加密类型
    	Input encryption type: (default "random")
```

## NEXT

* [ * ] 混淆加密
* [ * ] 客户端
