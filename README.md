## 介绍
小程序基于[magnetW](https://github.com/dengyuhan/magnetW)的API实现，要本地调试小程序，需要先搭建[magnetW](https://github.com/dengyuhan/magnetW)来提供接口

## 直接体验
<img src="screenshots/mini.jpg" width="180"/>

## 截图
<img src="screenshots/1.gif" width="250"/>

## 本地编译
由于小程序对请求的的限制，项目中用到了云函数，如果要在本地编译，还需要开通[云开发](https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html)  
>*测试appid无法使用云开发

修改[functions/requestGet](functions/requestGet/index.js)中的`baseUrl`为`magnetW`的访问根目录，上传云函数
