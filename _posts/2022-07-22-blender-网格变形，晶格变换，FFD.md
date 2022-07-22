---
date: 2022-07-22
layout: post
title: blender网格变形
subtitle: 'max的FFD修改器'
description: >-
  blender的网格变形操作，如何实现max的ffd变形
image: >-
  /assets/img/posts/2022/07/15/07.png
optimized_image: >-
  /assets/img/posts/2022/07/15/02.png
category: blog
tags:
  - blender
author: JinLoong
paginate: true
---
## 01.新建网格物体
![这是图片](/assets/img/posts/2022/07/15/01.png "新建网格物体")
    shift+A呼出新建菜单栏

## 02.添加分段
![这是图片](/assets/img/posts/2022/07/15/02.png "添加分段")
        1.tab进入编辑模式
        2.Ctrl+R添加分段，鼠标中间增加或减少分段数

## 03.新建晶格
![这是图片](/assets/img/posts/2022/07/15/03.png "shift+A新建晶格")

## 04.缩放晶格包裹住网格物体
![这是图片](/assets/img/posts/2022/07/15/04.png "缩放晶格包裹住网格物体")
        1.Shift+Z开启线框透视显示
        2.数字键盘1前视图
        3.S缩放

## 05.给物体添加晶格变换修改器并添加刚才新建的晶格
![这是图片](/assets/img/posts/2022/07/15/05.png "给物体添加晶格变换修改器并添加刚才新建的晶格")

## 06.来到晶格属性栏可以调整晶格细分
![这是图片](/assets/img/posts/2022/07/15/06.png "来到晶格属性栏可以调整晶格细分")

## 07.可以看到网格已经受晶格影响
![这是图片](/assets/img/posts/2022/07/15/07.png "来到晶格属性栏可以调整晶格细分")