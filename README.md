
# socket.io app

> 这是一个完整的即时通讯 APP web 版本。vue-socket.io master分支为 2.0 版本，原来的 1.0 版本请查看分支： old-code-example。
>包括一个web应用，以及一个服务端。前端部分用用socket.io-client 和 vue.js 完成，代码简单易懂。前端显示部分为高仿 腾讯TIM。服务端用 Node.js 和 socket.io-server 完成。

## 项目地址

1.0 版本代码：https://github.com/beautifulBoys/vue-socket.io/tree/old-code-example
2.0 版本代码：https://github.com/beautifulBoys/vue-socket.io.git

## 写在前面

  本项目所有用到的全部是目前前端最热门的技术 ! !

  通过本项目的学习与研究，你可以初步掌握vue的基本用法，css预处理器（less）的用法，router（路由）的用法，还可以加深了解vue-cli（脚手架）的使用，webpack的使用，babel编译代码...等等。

  前端变化莫测，学无止境。作者本人也在通过学习不断巩固和提高。如果你有极客精神，我们不妨一起进步。


## 项目在线预览
1.0 版本
点击访问：http://47.95.212.47:8888/pc/vue-socket/index.html#/

## 项目图片预览

<p align="center">
	<img src="https://github.com/beautifulBoys/beautifulBoys.github.io/blob/master/source/socket.io/images/start.gif" width="350px"/>
	<img src="https://github.com/beautifulBoys/beautifulBoys.github.io/blob/master/source/socket.io/images/none.jpg" width="350px"/>
</p>
<p align="center">
	<img src="https://github.com/beautifulBoys/beautifulBoys.github.io/blob/master/source/socket.io/images/talking.gif"/>
</p>
<p align="center">
	<img src="https://github.com/beautifulBoys/beautifulBoys.github.io/blob/master/source/socket.io/images/member.gif"/>
</p>
<p align="center">
	<img src="https://github.com/beautifulBoys/beautifulBoys.github.io/blob/master/source/socket.io/images/log.jpg"/>
</p>

## 项目组成

* vue.js 2.0
* socket.io
* vue-cli
* less
* webpack
* ES6
* eslint
* vue-router
* npm
* babel

## 项目安装及运行

``` bash
# 项目安装
npm install

# 打开server目录，命令行启动server.js(服务器)
node server.js

# 修改IP地址（src/components/room/room.vue 324行修改为自己的IP地址）
this.httpServer = io.connect('http://192.168.31.238:3000');// 修改为自己的IP

# 项目运行（浏览器访问 http://localhost:8085）
npm run dev

# 编译打包
npm run build
```


