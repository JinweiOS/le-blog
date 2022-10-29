---
title: 阿里云函数部署博客
---

## 详细步骤

1.先注册阿里云并开通函数服务
2.安装node.js，以提供npm命令使用
3.去安装 [Serverless-Devs](https://github.com/Serverless-Devs/Serverless-Devs), 具体的脚本如下

```shell
npm install @serverless-devs/s -g
```

4.使用s命令创建静态项目hexo
5.通过阿里云控制台的AccessKey管理创建ram子用户
6.为此子用户开通阿里云操作权限并创建AccessKey
7.在命令行中赋值AccessKeyId和AccessKeySecret
8.直接部署hexo阿里云函数
9.申请阿里云域名，在云函数的域名管理中配置cname解析
10.去ssl证书管理台申请免费的数字证书并在云函数域名管理中开启https
11.技术

