# WebServer

------

用C++实现的高性能WEB服务器，经过webbench压力测试可以实现8000左右QPS

## 功能

------

- 利用IO复用技术Epoll与线程池实现多线程的Reactor高并发模型；
- 利用状态机解析HTTP请求报文，实现处理静态资源的请求；

## 技术点

------

- 互斥锁
- 信号量
- Linux网络编程
- IO多路复用技术epoll
- 线程池

## 环境要求

------

- Linux
- C++14

## 核心业务流程图

------

![image](https://github.com/user-attachments/assets/157c18fc-a18c-4e75-81b2-d14d9aab023a)

