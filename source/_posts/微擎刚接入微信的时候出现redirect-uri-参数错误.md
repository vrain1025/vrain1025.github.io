---
title: 微擎刚接入微信的时候出现redirect_uri 参数错误
tags: []
id: '860'
categories:
  - - 个人原创
date: 2018-11-14 14:00:13
---

提示 `微信登陆失败 10003redirect_uri 参数错误`   或者电脑端`提示redirect_uri 参数错误`出现这个问题是由于微信没有对域名进行授权，解决方法很简单，打开微信公众号后台，然后在公众号设置，功能设置里，网页授权域名把微擎的域名填写进去就OK了。