---
title: 在GitHub上架设博客网站
toc: true
date: 2025/4/8 
---

## 简单介绍

Github提供了Github Pages来帮助我们架设静态网站，Github Pages是一项免费的静态文件部署服务, 通过它可以把生成的静态网站托管在Github上。
本篇博客不负责介绍其他搭建网站方式和各自的优劣，我们直接开始吧。

## Step 1：注册一个github账号

访问[Github](https://github.com/)并点击 sign up 进行注册，需要提供用户名、密码和邮箱，不需要手机号。
用户名不允许重复，顺带一提，在Github上搭建的个人网站，用户名最终会出现在网址上，所以记得取个自己喜欢的名字！

接着Github会询问你是否需要付费使用。免费服务足够满足大部分开发者的需求了，付费服务主要面向团队和企业。

此后Github会问你使用Github的目的、熟练度等等，类似于用户调研，照实填写即可。

之后Github会向你注册时填写的邮箱发送验证信息，在邮件中打开链接进行确认，账号就顺利激活了。

## Step 2：创建一个仓库

点击 sign in 登录你的Github账号，在个人（或组织）的首页找到头像下“Your repositories”的选项，点击new新建一个仓库。

步骤包括：命名，描述（选填），选择公开与否（默认是public，公开的仓库所有人都可以访问，private则只有个人可访问，对组织而言则是部分人可访问，同样也影响最后生成的网站访问权限。不过这个选项是随时可以修改的），选择是否生成一个README（介绍文件），点击“create repository”创建。

接下来会有一大堆关于git操作的指示，新手可以先跳过，直接点击create a new file构建一个新文件 index.html，（静态http文件托管服务的默认访问文件就是index.html）用途是渲染网页。

随后点击导航栏中的设置Settings，找到侧边栏中的Pages,source选择 deploy from a branch, branch里的分支改成你的主分支（main, master, gh-pages等等），目录默认是根目录。
生成站点页面时Github Pages会在你选择的分支里找到相关文件。
这个时候刷新页面就可以看到Github生成的网址了。

## Step 3：配置主题

参见[Jekyll主题配置]()；[Hexo主题配置]()。

## Step 4：写博文

-- 未完待续 --
