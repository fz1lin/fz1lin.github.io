

## 常用指令和发布文章
- 常用命令

```php
hexo new "postName"        //新建文章
hexo new page "pageName"        //新建页面
hexo g          //生成静态页面至public目录
hexo server         //开启预览访问端口（默认端口4000，'ctrl + c'关闭server）
hexo deploy         //将.deploy目录部署到GitHub
```

- 发布文章
```php
hexo clean
hexo g
hexo d
hexo d -g  //生成部署
hexo s -g  //生成预览
```
