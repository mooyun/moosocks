# moosocks

大佬们是真正的从0到1，而我，只能站在巨人的肩膀上从0到1，实现自己的代理，手锤GWF。。。


#### 说明
**心得碎碎念**
回首大一下学期的《计算机网络》和大二上学期的《TCP/IP与网络编程》，晦涩难懂，期末成绩均在80+，我都不知道怎么考的，写此项目及其艰难，但又似曾相识，可不是吗，理论都是书上的，又想起那三本奇厚的《UNIX网络编程》，大佬们就是大佬，功力深厚。。

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