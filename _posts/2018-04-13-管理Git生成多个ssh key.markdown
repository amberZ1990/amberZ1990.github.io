---
layout:     post
title:      "git"
subtitle:   ''
date:       2018-04-13
author:     "Amber"
header-img: "img/post-bg-2017.jpg"
tags:
    - git
    - 前端开发
---

### “管理Git生成多个ssh key”

 - 1.生成key的命令ssh-keygen -t rsa -C “Your Email Address” -f 'Your Name'，-f后面给的生成key的名字，如果没有指定新的名字，那么每次ssh-keygen生成的名字相同，就会发生覆盖同名文件的情况的发生

 - 2.生成两个key后，添加到对应服务器的ssh kyes管理设置中。

 - 3.本地添加私钥
    > 本地添加私钥名命令ssh-add ~/.ssh/Your Key Name，如果出现“Could not open a connection to your authentication agent”的问题，可以执行命令ssh-agent bash，再运行添加命令。另外，可用通过
    >>
        ssh-add -l 查看私钥列表
        ssh-add -D来清空私钥列表

#### 原文地址 : [https://blog.csdn.net/u012365926/article/details/52293036]( https://blog.csdn.net/u012365926/article/details/52293036 )