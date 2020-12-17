<h1 align="center">前端技术总结</h1>

国内镜像:[码云](https://gitee.com/xv700/Message-communication-for-web)   

## 场景问题

###  001.前端跨域

-  跨域定义    

> 即请求的地址与被请求的地址协议头、域名、端口有一个不一样就叫跨域。相反,不跨域即叫同源。

| http://www.example.com/detail.html | 与以下地址对比 |  
| --- | --- |  
| http://api.example.com/detail.html | 不同源，子域域名不同，根域名相同 |  
| http://nav.qianlimu.net/ | 不同源，域名完全不同 |  
| https://www.example.com/detail.html | 不同源，协议不同 |  
| http://www.example.com:8080/detail.html | 不同源，端口不同 |  
| http://www.example.com/other.html | 同源，只是目录不同 |  

-  可能出现的场景

-  前端跨域解决方案

### 002.网页消息传递

#### 定义  

> 在浏览器中，两个不同页面（A页面的window ！= B页面的window）网页之间的消息传递。

点击阅读：[网页消息传递](/002.Message_Communication)  


### 003.Javascript中事件冒泡的问题


## 原生js问题

### 001.Blob的使用

### 002.Web Worker
 
### 003.IndexedDB 

### 004.Canvas

### 005.WebSocket

非原生的分离出去

## js加密

https://github.com/ricmoo/aes-js

## 图片压缩

https://github.com/fengyuanchen/compressorjs


