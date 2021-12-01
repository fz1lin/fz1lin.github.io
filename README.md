

## 常用指令和发布文章
- 常用命令

```php
hexo new "postName"        //新建文章
hexo new page "pageName"        //新建页面
hexo g          //生成静态页面至public目录
hexo server         //开启预览访问端口（默认端口4000，'ctrl + c'关闭server）
hexo deploy         //将.deploy目录部署到GitHub
```

- 常用命令
```php
hexo clean
hexo g
hexo d
hexo d -g  //生成部署
hexo s -g  //生成预览
```

发布文章
终端cd到blog文件夹下，执行如下命令新建文章：

hexo new "xxx"
名为xxx.md的文件会建在目录.../blog/source/_posts下。

所有的文章都会以md形式保存在_post文件夹中，只要在_post文件夹中新建md类型的文档，就能在执行hexo g的时候被渲染。新建的文章头需要添加一些信息，如下所示：

```php
---
title: xxx    //在此处添加你的标题。
date: 2016-10-07 13:38:49   //在此处输入编辑这篇文章的时间。
tags: xxx    //在此处输入这篇文章的标签。
categories: xxx    //在此处输入这篇文章的分类。
---
```
文章编辑完成后，终端cd到blog文件夹下，依次执行如下命令来发布：
```php
hexo g
hexo d
```
基于 `GitHub Pages + Hexo `
