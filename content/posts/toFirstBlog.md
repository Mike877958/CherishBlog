---
date: '2026-04-06T22:07:52+08:00'
title: 'To First Blog'
---
## 软件准备
#### - powershell
#### - node.js
#### - git

## 代码操作
#### 1. init
```bash
# 创建站点目录，将"MyBlog"替换为你的站点名称
hugo new site MyBlog --format yaml
# 进入目录
cd MyBlog
 初始化 Git 仓库
git init
```
#### 2.git theme
```bash
# 安装
git submodule add https://github.com/hcllmsx/hugo-jijian.git themes/jijian
# 日后更新主题
git submodule update --remote
```
#### 3. create posts
#### 4. config
#### 5. run