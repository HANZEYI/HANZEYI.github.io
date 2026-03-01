---
title: 发布前记得输入hexo clean哦
date: 2026-03-02 05:51:16
tags: [使用笔记]
---
写完或修改完文章后，在 D:\myblog 目录下执行以下命令，把更新推送到线上：
# 1. 清理旧的生成文件
hexo clean

# 2. 生成新的静态博客页面
hexo generate

# 3. 部署到 GitHub Pages
hexo deploy

或者用一条简写命令，效果完全一样：

hexo clean && hexo g -d