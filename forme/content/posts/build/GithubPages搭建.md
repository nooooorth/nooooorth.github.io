---
title: "利用GitHubPage搭建个人博客"
date: 2023-09-09T08:22:53Z
lastmod: 2023-09-09T08:22:53Z
author: ["nooooorth"]

categories:
- 小小小小玩意

tags:
- blog
- hugo
- github
- papermod

keywords:
- Github
- 免费建站
- 无需配置本地环境

description: "白嫖Github！" # 文章描述，与搜索优化相关
summary: "利用Github codespaces pages搭建个人blog" # 文章简单描述，会展示在主页
weight: # 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
slug: ""
draft: false # 是否为草稿
comments: true
showToc: false # 显示目录
TocOpen: true # 自动展开目录
autonumbering: true # 目录自动编号
hidemeta: false # 是否隐藏文章的元信息，如发布日期、作者等
disableShare: true # 底部不显示分享栏
searchHidden: false # 该页面可以被搜索到
showbreadcrumbs: true #顶部显示当前路径
mermaid: true
cover:
    image: ""
    caption: ""
    alt: ""
    relative: false
---
# Github纯白嫖攻略💕

没有稳定访问外网的能力的话建议绕道~

## 1. 准备构建环境
- 💻能稳定上网的设备（能浏览网页即可）
- 😊耐心 - *patiences is key of life*
- 💡满满的创意

## 2. [Github Page](https://pages.github.com/)创建

### 2.1 开发环境构建
- 在Github上创建一个`username.github.io`的 **public** 仓库
- 在当前仓库下创建一个代码空间(Free!!!)
![点击+号创建](/img/image-1.png)
- 在网页或VsCode中连接到你的Github CodeSpace
- 至此你的博客开发环境搭建完成👏

### 2.2 博客构建
该教程使用了Hugo构建博客
- 🚀 构建更快,build for future
- 🀄  简单易用，符合需求

构建过程
- 打开terminal，安装hugo
![打开terminal](/img/20230915165932-convert.gif)
```bash
# 切换到root用户
sudo su 

# 安装hugo
apt-get update
apt-get install hugo

# 验证
hugo version
# 安装成功 hugo v0.118.2-da7983ac4b94d97d776d7c2405040de97e95c03d linux/amd64 BuildDate=2023-08-31T11:23:51Z VendorInfo=gohugoio 
```

<!-- more --> 
