# hexo +github pages搭建个人博客

## 环境搭建

安装nodejs,git,v2ray

v2ray实现科学上网，终端下载资源，上传资源

## 安装hexo

```
npm install hexo-cli -g
hexo init myblog 
cd myblog 
npm install 
生成静态网站
hexo g 生成项目文档
hexo s 启动服务
修改主题的时候需要执行hexo clean 清除原来的配置
hexo d 上传静态文件到github
hexo new "My New Post" 创建一篇文章
配置文件_config.yml
title: lzj
subtitle: ''
description: 'hexo blog'
keywords: blog
author: lizejun
language: zh-hans  ## zh-CN
timezone: 'Asia/Shanghai'
url: https://lizeju.github.io/hexo_blog/ ## 首页的url,
theme:   butterfly ##  hexo-theme-matery-master  hexo-theme-next  butterfly
deploy:
  type: git
  repo: https://github.com/LIZEJU/hexo_blog.git
  branch: main


butterfly 主题展示的网站
https://butterfly.js.org/
https://github.com/jerryc127/hexo-theme-butterfly butterfly github地址
git clone -b master https://github.com/jerryc127/hexo-theme-butterfly.git themes/butterfly 下载butterfly主题到主题目录
npm安装 butterfly相关
npm install hexo-renderer-pug hexo-renderer-stylus


```

## github

### github配置pages，access token

```
创建仓库名称：hexo_blog  权限public
在仓库页面点击settings ,在code and automation 下面选择pages
在build and deployment选择source中的deploy from a branch 
在branch下选择分支以及该分支源码下的某个目录 root 代表根目录 doc代表 根目录下的doc目录
然后再生成上传github的access token 

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EVDAGMW3BuOISEKcDssssspwdkjsdjkfhajdsakjfhksdfkjbsdb
再给该token设置权限

```

### ![image-20221217040514308](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221217040514308.png)

![image-20221217040530837](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221217040530837.png)

![image-20221217040547178](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221217040547178.png)

![image-20221217040611634](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221217040611634.png)

![image-20221217040651214](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221217040651214.png)

### 查看github pages 页面

```
https://github.com/LIZEJU/hexo_blog github仓库地址

https://lizeju.github.io/hexo_blog/ hexo在github pages页面
查看上传的静态页面的动态，啥时候可以访问
仓库地址的actions按钮
```

![image-20221217041333697](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221217041333697.png)

![image-20221217042103736](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221217042103736.png)

## 问题

1. md文件中的图片文件在生成的静态页面中显示不出来。md文件的图片文件解析有问题
2.  md文件需要注意的地方 title

    ```
    ---

    title: hexo +github pages搭建个人博客

    date: 2022-12-17 04:30:20

    tags:

    ---
    开头需要写这个
    ```
