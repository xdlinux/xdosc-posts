---
layout: post
title: "软件源调整"
date: 2017-11-15
author: ckj
categories: announcements
---

## changelog

1. 新增 bioconductor 镜像（[bioc][1]）—— R语言中的生物信息学工具库。
2. 删除 Debian 的 armhf 镜像；删除 Fedora 25 的 i386 镜像。
3. 新增 Fedora 27。

[1]: https://linux.xidian.edu.cn/mirrors/bioc/

## related issues

1. [\#11 \[镜像申请\] R-bioconductor](https://linux.xidian.edu.cn/git/xdlinux/issues/issues/11)
2. [\#12 Fedora 27 发布](https://linux.xidian.edu.cn/git/xdlinux/issues/issues/12)

## explaination

选择删除这两个镜像的原因是

1. 硬盘空间不足。
2. Debian armhf 和 Fedora i386 使用率极低。
3. Fedora 25 即将 EOL。
