---
title: 使用hexo-nexT搭建个人博客的用法记录
date: 2020-05-28 15:37:58
tags: 
    - 标签用法
    - hexo
    - nexT
categories: 
    - nexT分类用法
    - 子分类
---

## 设置文章在首页展示的内容
首页中展示本文的这些信息
<!--more-->

这段文本不应该展示首页

## 关于多台机器同步
git clone git@github.com:bigwritejc/bigwritejc.github.io.git blog

cd blog 
sudo apt-get install nodejs
sudo apt-get install npm

sudo npm install hexo-cli -g
sudo npm install hexo-deployer-git --save

npm audit fix

hexo g
hexo s


## 关于本地图片的引用
![](hexo-nexT/hw1.jpg)



