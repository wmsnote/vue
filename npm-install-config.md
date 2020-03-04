---
title: 1. npm安装参数设置
tags: vue,web
notebook: vue
---

* npm(node package manager) 是nodejs的包管理器, 用于node插件管理(包括安装 卸载 管理依赖等)
* cnpm 因为npm安装插件是从国外服务器下载,受网络影响大,可能出现异常,所以我们乐于分享的淘宝团队分享了使用国内镜像来代替国外服务器

`npm install -gd express --registry=http://registry.npm.taobao.org`

永久设置: `npm config set registry http://registry.npm.taobao.org`

`npm install -g --save --dev vue-cli`


安装cnpm

`npm install -g cnpm --registry=http://registry.npm.taobao.org`


**使用cnpm代替npm命令,使用方式和参数完全相同, 唯一区别是cnpm使用国内淘宝源**

安装vue-cli

```sh
npm install -g @vue/cli
npm install -g @vue/cli-service-global
vue --version
```














