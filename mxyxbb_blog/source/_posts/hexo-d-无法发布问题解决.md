---
title: hexo d 无法发布问题解决
date: 2019-11-11 23:24:15
categories: 
    - 新手上路
tags: 
    - 标签1
---
deploy:
  type: git
  repository: git@github.com:xxx/xxx.github.io.git
  branch: master

config文件的repo地址改为上述格式后，“hexo d”命令即可正常使用