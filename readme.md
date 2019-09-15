# 学习json-server

## json-server可以干什么？

在实际工作中，前端工程师免不了要与后端进行交互，当后端工程师的接口没有写完的时候(但是已经定义好)，这个时候就需要前端工程师自己mock虚拟的数据,json-server是一个不错的工具

## 安装

`npm i json-server -D`

## 请求与发送需要注意的点

get 正常请求

但是对于数据修改的请求均加上

```
headers: {
    "Content-Type": "application/json"
} 
```
