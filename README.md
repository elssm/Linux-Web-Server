#### 简介

本仓库包含两个并发服务器项目

- 采用epoll实现的并发服务器
- 采用libevent实现的并发服务器

本项目是在学习了Linux系统编程和网络编程之后完成的
[Linux系统编程](https://www.bilibili.com/video/BV1KE411q7ee)
[Linux网络编程](https://www.bilibili.com/video/BV1iJ411S7UA?p=1)

在写并发服务器的过程中，对`Tcp`,`Socket`和`多线程多进程`都有了更深的了解。

#### 启动方式

```c
./server port dir
```

例如

```
./server 9527 /home/elssm
```

#### 请求目录

![请求目录](https://github.com/elssm/Linux-Web-Server/blob/main/photo/1.png)

![请求目录](https://github.com/elssm/Linux-Web-Server/blob/main/photo/2.png)

#### 请求文本

![请求文件](https://github.com/elssm/Linux-Web-Server/blob/main/photo/3.png)

![请求文件](https://github.com/elssm/Linux-Web-Server/blob/main/photo/4.png)

#### 请求图片

![请求图片](https://github.com/elssm/Linux-Web-Server/blob/main/photo/5.png)

![请求图片](https://github.com/elssm/Linux-Web-Server/blob/main/photo/6.png)

#### 请求不存在的路径

![请求图片](https://github.com/elssm/Linux-Web-Server/blob/main/photo/7.png)
