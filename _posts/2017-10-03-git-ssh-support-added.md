---
layout: post
title: "Git 服务支持 SSH 了"
date: 2017-10-03
author: ckj
categories: blog
---
应 [sz1 同学的反馈][1]，我们的 `Git 服务` 支持 `SSH` 了。

[1]: https://linux.xidian.edu.cn/git/xdlinux/issues/issues/1 "issue 1"

Q: 有什么好处呢？  
A: `push` 的时候不用输密码了。

Q: 如何使用？  
A: 在用户设置中添加 `SSH 公钥`，并且设置本地仓库的 `remote url` 为 `gogs@linux.xidian.edu.cn:user/repo.git`

网址： [linux.xidian.edu.cn/git/](https://linux.xidian.edu.cn/git/)

另一个消息是配置好了邮件提醒，注册需要验证邮件了。

流量有限，主要面向校内服务，不 ban 校外 ip 是因为考虑到校外应急使用。

