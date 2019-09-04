# Implementation-of-TCP-File-Transfer-in-C-under-Linux
Linux下C实现TCP文件传输

#### 使用说明

1. 终端下输入 make
2. 终端 就可以运行 服务端和客户端了  ./server  ./client

### 功能说明
支持TCP文件传输模式

    cmd 通道（TCP）
    
	list 显示当前目录所有文件名
  
	cd 切换目录
  
	put 上传
   
	get 下载
  
    data 通道（TCP/UDP)
    
    同名文件覆盖
    


  客户端和服务端的TCP文件传输，客户端可以上传文件到服务端，也可以从服务端下载文件，还可以查看和修改服务端的工作目录（临时）。

#### 相关图片

![编译](https://images.gitee.com/uploads/images/2019/0823/204156_4e89811a_5140590.png "屏幕截图.png")
![运行服务端和客户端](https://images.gitee.com/uploads/images/2019/0823/204225_ab4b56ed_5140590.png "屏幕截图.png")

过多效果图请参考博客：https://blog.csdn.net/Ikaros_521/article/details/99120280
