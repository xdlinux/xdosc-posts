---
layout: post
title: "Anaconda 镜像更新"
date: 2017-12-20
author: ckj
categories: announcements
---

一个对于 Windows 和 macOS 用户的好消息：

虽然没有人重开 issue，但是从 nginx log 中还是能看到：
有许多 Windows 和 macOS 用户想要使用 Anaconda 镜像。

由于 Homebrew-Bottles 上游镜像体积从 700G 减小到 100G，
我们有了足够的空间同步 Anaconda。

现已添加 `win-64` 和 `osx-64` 的 `pkg` 仓库，加上原有的 `linux-64`，
覆盖了 Anaconda 目前支持的全部 `x86_64` 平台。

## 使用说明

见[wiki](https://linux.xidian.edu.cn/wiki/mirror-help/anaconda)

## 问题反馈

欢迎测试、[反馈](https://linux.xidian.edu.cn/git/xdlinux/issues/issues/15)
