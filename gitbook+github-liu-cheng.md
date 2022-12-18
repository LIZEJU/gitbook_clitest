# gitbook+github流程

* 在github上添加内容，同步到对应的github仓库
* 在本地执行git操作，将github仓库pull下来，然后进入（checkout）静态页面对应的分支,将\_book文件夹下的页面copy到项目的根目录，push到静态页面分支的仓库
* 等待gitpages自动加载解析静态页面分支仓库的页面，这里不需要操作，看在action选项可以看到是否加载完毕
* 最后访问gitpages 的url链接，完毕。



## 注意

* gitbook创建项目的时候，第一个文件必须是[README](https://github.com/LIZEJU/k8s2#readme)

## 文档

* [gitbook官方文档](https://docs.gitbook.com/tour/editor/rich-text)
* [markdown文档](https://markdown.com.cn/basic-syntax/links.html)

## gitbook问题

```
gitbook 

* [tool](https://lizeju.github.io/gitbook\_clitest/)
https://lizeju.github.io/gitbook_clitest/ 这个正确的链接
在gitbook同步到github的时候，链接发生变化
https://lizeju.github.io/gitbook\_clitest/
需要到github仓库里面修改
```
