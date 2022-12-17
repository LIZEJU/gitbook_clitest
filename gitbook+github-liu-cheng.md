# gitbook+github流程

* 在github上添加内容，同步到对应的github仓库
* 在本地执行git操作，将github仓库pull下来，然后进入（checkout）静态页面对应的分支,将\_book文件夹下的页面copy到项目的根目录，push到静态页面分支的仓库
* 等待gitpages自动加载解析静态页面分支仓库的页面，这里不需要操作，看在action选项可以看到是否加载完毕
* 最后访问gitpages 的url链接，完毕。
