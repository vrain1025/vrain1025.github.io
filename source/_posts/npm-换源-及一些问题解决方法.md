---
title: NPM 换源 及一些问题解决方法
tags: []
id: '592'
categories:
  - - 网络收集
date: 2017-03-21 17:01:50
---

npm config set strict-ssl false 镜像使用方法（三种办法任意一种都能解决问题，建议使用第三种，将配置写死，下次用的时候配置还在）: 1.通过config命令 npm config set registry https://registry.npm.taobao.org npm info underscore （如果上面配置正确这个命令会有字符串response） 2.命令行指定 npm --registry https://registry.npm.taobao.org info underscore 3.编辑 ~/.npmrc 加入下面内容 registry = https://registry.npm.taobao.org 搜索镜像: https://npm.taobao.org 建立或使用镜像,参考: https://github.com/cnpm/cnpmjs.org