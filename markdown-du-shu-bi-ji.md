# markdown读书笔记

\[TOC]

## 介绍

### 扩展语法

```
GFM 扩展语法 （github flavored markdown） github是全球最大的程序员“交友”网站
commonMark 标准语法 （http://commonmark.org/）

Markdown 编 辑 器 （ 如 Typora 、 熊 掌 记 、Ulysses）


```

### 语法

````
视图-选择源代码模式
标题
#一级标题
##二级标题
标题
----
标题
===

粗体和斜体
粗体
两个*和两个_组成，中间是文字
斜体
一个*和一个_组成，中间是文字


有序列表和无序列表
数字+ 英文句号 + 空格 + 内容
* + 空格 + 内容
- + 空格 + 内容

嵌套列表
+ 列表内容
tab + 第二层列表
tab + tab + 第三层列表

分割线
---
***
___

插入图片
![图片替代文字](图片地址)
图片可以是本地图片的地址，也可以是网络图片的地址
![图片](https://t7.baidu.com/it/u=1595072465,3644073269&fm=193&f=GIF)


链接
文字链接
[链接文字](链接地址)
[图片](https://t7.baidu.com/it/u=1595072465,3644073269&fm=193&f=GIF)


网址链接
<>
<https://www.baidu.com>


> 引用内容

删除线
~~被删除的文字~~

表情代码
:smile:
:+1: 加1 
:-1:
:clap: 鼓掌
:laughing: 笑


自动链接
`www.baidu.com`

表格
|name|age|
|---|---|
|lzj|19|

任务列表
- [] 未勾选
- [x] 已勾选

围栏代码块

​```
​```

~~~
~~~


锚点，也称为书签
用来标记文档的特定位置
[锚点描述](#锚点名)


````

| name | age |
| ---- | --- |
| lzj  | 19  |

* [ ] \[] 未勾选
* [x] 已勾选

```

三大地方
```

[锚点描述](broken-reference)

## typora

```
下载地址
https://typora.io/#download

安装Pandoc
标记语言转换工具
https://github.com/jgm/pandoc/releases/latest
```

[https://typora.io/#download](https://typora.io/#download)

https://github.com/jgm/pandoc/releases/latest

## vscode

https://code.visualstudio.com/

### 安装chatgpt插件

```
chatgpt
使用chatgpt请输入问题，显示当前模式无法使用

ChatGPT: 请输入问题：直接对 ChatGPT 提问
ChatGPT: 添加测试代码：为当前选中的代码，或者当前文件添加测试代码
ChatGPT: 代码为什么有问题(需要同时选中报错)：询问代码出现的问题，需要将报错也一起选中
ChatGPT: 优化这部分代码：对当前选中的代码，或者当前文件，进行优化或者重构
ChatGPT: 解释这部分代码：对当前选中的代码，或者当前文件，进行解释
ChatGPT: 执行自定义命令1：添加一个对选中代码，或者当前文件执行的自定义命令1，添加后可以直接执行
ChatGPT: 执行自定义命令2：添加一个对选中代码，或者当前文件执行的自定义命令2，添加后可以直接执行

作者：何时夕
链接：https://juejin.cn/post/7175770569739075641
来源：稀土掘金
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。

google下载chatgpt插件
使用，和google搜索一样，但是需要登录，登录操作会遇到chat open api不能使用
```

![image-20221216060114889](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221216060114889.png)

![image-20221216060304280](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221216060304280.png)

![image-20221216060339257](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221216060339257.png)

![image-20221216060458443](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221216060458443.png)

### 安装中文插件

```
快捷键
ctrl + shift + x 

输入chinese 
安装chinese simplified 
安装后重启生效

切换语言
快捷键 ctrl + shift + p 
输入Configure Display language 
选择中文
会提示重启

```

![image-20221212180646022](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221212180646022.png)

![image-20221212181100280](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221212181100280.png)

![image-20221212181119387](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221212181119387.png)

### 安装主题插件

```
ctrl + shift + p 快捷键进入插件下载的地方
搜索One Dark Pro
安装
选择主题：
管理--颜色主题-再选择下载的这个主题
```

![image-20221212181521454](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221212181521454.png)

![image-20221212181935026](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221212181935026.png)

### 快捷键插件

```
快捷键插件有
· IntelliJ IDEA Key Bindings for Visual Studio Code
· Sublime Text Keymap and Settings Importer
· Visual Studio Keymap
· Atom Keymap
· Vi m
· Notepad++keymap
· Eclipse Keymap

小提示： 笔者使用的是【IntelliJ IDEA Key Bindings for
Visual Studio Code】，IntelliJ IDEA是JetBrains系列产品中的一
员，它的快捷键也同样适用于 WebStorm、PyCharm等IDE（Integrated
Development Environment，集成开发环境）。

```

### 安装插件

```
ctrl +shift +x
搜索 Markdown Preview Enhanced
简称 MPE 
超级Markdown插件MPE





```

### 插入目录

```
ctrl +shift +p 进入命令控制面板
搜索Markdown Preview Enhanced:Create TOC

```

### 引用文件

```
@import "文明名.扩展名"

引用图片

@import "x.jpg" {width="200px" height="150px" title="x" alt="xxx"}

引用csv文件
@import "x.csv"

MPE使用reveal.js来渲染幻灯片
幻灯片通过<!--slide-->来分页



```

### 导出文件

#### 导出pdf文件

```
通过工具puppeteer 导出pdf文件
npm install -g puppeteer 

安装完成后，只需在预览界面上单击鼠标右键，选择【Chrome
(Puppeteer)】→【PDF】即可，PDF文件会被导出到当前目录中，而且
会被自动打开。

导出PDF文件——（Prince）
其 他 操 作 系 统 的 安 装 方 法 请 参 考
https://www.princexml.com/doc-install/。


安 装 完 成 后 ， 只 需 在 预 览 界 面 上 ， 单 击 鼠 标 右 键 ， 选 择
【PDF(prince)】即可，PDF文件会被导出到当前目录中，而且会被自
动打开。

如果我们想在修改Markdown文件之后，自动导出最新的PDF文件，
只需在Markdown文件头部加上如下代码

---
export_on_save:
	prince: true
---

```

### 高效编辑

#### 命令面板

```
ctrl + p 
进行快速打开文件

```

#### 自动保存

```
VS Code提供了自动保存的功能，它有3种保存策略

1）afterDelay：当文件修改超过一定的时间（默认是1000ms）时自动保存。
2）onFocusChange：当编辑器失去焦点时自动保存更新后的文件。
3）onWindowChange：当窗口失去焦点时自动保存更新后的文件。

VS Code默认使用的是第1种策略，执行：菜单栏→【文件】
→【自动保存】，开启自动保存，此后，当文件修改超过1000ms时就
会自动保存。
如果想修改延迟时间，可以单击活动栏下面的【管理】图标
→【设置】→在搜索设置输入框中输入[自动保存]，搜索结果如下图
所示。


```

![image-20221215071349655](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221215071349655.png)

#### 智能感知--自动补全

```
操作步骤：【管理】→【键盘快捷方式】→在搜索框输入
[Trigger Suggest]（触发建议）→修改快捷键。


ctrl + i 
注意： 关于快速插入代码片段的示例，我们后面再讲。如果想
使用更多快捷键和自动补全的功能，需要安装一个扩展插件——
Markdown All in One。
```

![image-20221215071855348](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221215071855348.png)

#### Markdown All in One

```
markdown 插件 快捷键
```

#### 自动代码片段-x

```
【 管 理 】 → 【 用 户 代 码 片 段 】 → 在 弹 出 的 面 板 中 选 择
【markdown.json】，如下图所示

"insert table":{
		"prefix": "table",
		"body": {
			"|one|two|three|",
			"|---|---|---|",
			"|1|2|3|"
		}
	},
```

#### 语法检查

```
安装markdownlint以后，它会自动对Markdown文件进行检查


```

#### 打字时的酷炫效果

```
需要注意的是，Power Mode在安装后并不会直接开启，需要设置
一 下 。 开 启 Power Mode 的 方 法 ： 【 管 理 】 → 【 设 置 】 → 输 入
[Powermode]→勾选【Enable to active POWER MODE!!!】


```

#### 禅模式

```
什么是禅模式?
禅是一种基于“静”的行为，是一种让我们专注于写作的模式。
打开VS Code→【菜单栏】→【查看】→【外观】→【切换禅模
式】。

```

## 写幻灯片-reveal.js

```
还有很多工具支持直接使用Markdown写幻灯片，例
如 ， 比 较 简 单 的 Marp 、 在 命 令 行 中 写 作 的 mdp ， 以 及 漂 亮 的
Deckset （ 收 费 ） 。 也 有 一 些 强 大 的 写 幻 灯 片 的 开 源 工 具 ， 如
nodeppt、shower、remark、impress.js和reveal.js，其中比较流行
的是reveal.js。

reveal.js是一个使用HTML和Markdown快速创建和演示幻灯片的工
具，它提供了很多实用的功能，也提供了很多第三方插件来增强效
果。


```

### 环境搭建

```
STEP 1，搭建reveal.js使用环境。
使用reveal.js必须先安装Node.js和Git，请参考附录。
https://nodejs.org/zh-cn/download/
https://www.runoob.com/nodejs/nodejs-install-setup.html

https://www.runoob.com/git/git-install-setup.html
https://git-scm.com/download/win

C:\Program Files\nodejs\

path
PATH=C:\Windows\system32;C:\Windows;C:\Windows\System32\Wbem;C:\Windows\System32\WindowsPowerShell\v1.0\;C:\Windows\System32\OpenSSH\;C:\Program Files\Calibre2\;C:\Program Files\Intel\WiFi\bin\;C:\Program Files\Common Files\Intel\WirelessCommon\;C:\Program Files (x86)\dotnet\;C:\Program Files\nodejs\;C:\Users\l\AppData\Local\Programs\Python\Python39\Scripts\;C:\Users\l\AppData\Local\Programs\Python\Python39\;C:\Users\l\AppData\Local\Microsoft\WindowsApps;C:\Python27\Scripts;C:\Python27;;C:\Windows\System32\Wbem;C:\Users\l\AppData\Local\Programs\Microsoft VS Code\bin;C:\Users\l\AppData\Roaming\npm


node --version
v18.12.1


/etc/gitconfig 文件：系统中对所有用户都普遍适用的配置。若使用 git config 时用 --system 选项，读写的就是这个文件。
~/.gitconfig 文件：用户目录下的配置文件只适用于该用户。若使用 git config 时用 --global 选项，读写的就是这个文件

$ git config --global user.name "runoob"
$ git config --global user.email test@runoob.com

C:\Program Files\Git

C:\Users\l>git --version
git version 2.39.0.windows.1

C:\Users\l>path
PATH=C:\Windows\system32;C:\Windows;C:\Windows\System32\Wbem;C:\Windows\System32\WindowsPowerShell\v1.0\;C:\Windows\System32\OpenSSH\;C:\Program Files\Calibre2\;C:\Program Files\Intel\WiFi\bin\;C:\Program Files\Common Files\Intel\WirelessCommon\;C:\Program Files (x86)\dotnet\;C:\Program Files\nodejs\;C:\Program Files\Git\cmd;C:\Users\l\AppData\Local\Programs\Python\Python39\Scripts\;C:\Users\l\AppData\Local\Programs\Python\Python39\;C:\Users\l\AppData\Local\Microsoft\WindowsApps;C:\Python27\Scripts;C:\Python27;;C:\Windows\System32\Wbem;C:\Users\l\AppData\Local\Programs\Microsoft VS Code\bin;C:\Users\l\AppData\Roaming\npm

https://www.runoob.com/w3cnote/npm-slow-use-cnpm.html
淘宝 NPM 镜像地址：https://npm.taobao.org/
npm install -g cnpm --registry=https://registry.npmmirror.com


STEP 2，下载reveal.js。
方法1：使用浏览器下载。
打 开 https://github.com/hakimel/reveal.js→ 【 Clone or
download】→【Download ZIP】→解压。

git clone https://github.com/hakimel/reveal.js.git
STEP 3，查看示例。
打开reveal.js文件夹，在根目录中找到index.html，然后使用VS
Code打开

<div class="reveal">
			<div class="slides">
				<section>Slide 1</section>
				<section>Slide 2</section>
			</div>
</div>
从这段代码可以看出，在HTML中，幻灯片标记的层次结构
是.reveal >.slides > section。关于section，我们可以理解为分页
标签，每一张幻灯片都是使用<section>标签包裹的。

ctrl + f5 运行页面

STEP 4，创建我们的第一个幻灯片。
复制index.html并重命名为first.html，使用VS Code打开，修改
核心代码，具体如下

npm install -g cnpm --registry=https://registry.npmmirror.com
cnpm install 
npm install 


cnpm install 
cnpm : 无法加载文件 C:\Users\l\AppData\Roaming\npm\cnpm.ps1，因为在此系统上禁止运行脚本

管理员运行powershell
PS C:\Users\l\Downloads\reveal.js-master> set-ExecutionPolicy RemoteSigned

执行策略更改
执行策略可帮助你防止执行不信任的脚本。更改执行策略可能会产生安全风险，如 https:/go.microsoft.com/fwlink/?LinkID=135170
中的 about_Execution_Policies 帮助主题所述。是否要更改执行策略?
[Y] 是(Y)  [A] 全是(A)  [N] 否(N)  [L] 全否(L)  [S] 暂停(S)  [?] 帮助 (默认值为“N”): y
PS C:\Users\l\Downloads\reveal.js-master> cnpm install

```

### 搭建完整的项目环境

```
安装nodejs git 
git clone reveal.js
vscode 打开reveal.js项目
npm install 安装依赖包
npm start 启动
npm start -- --port=7000 启动
http://localhost:8000 访问


```

### nodejs升级到最新稳定版本

```
root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1# npm install -g n

added 1 package, and audited 2 packages in 2s

found 0 vulnerabilities
root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1# n stable
  installing : node-v18.12.1
       mkdir : /usr/local/n/versions/node/18.12.1
       fetch : https://nodejs.org/dist/v18.12.1/node-v18.12.1-linux-x64.tar.xz
     copying : node/18.12.1
   installed : v18.12.1 (with npm 8.19.2)

Note: the node command changed location and the old location may be remembered in your current shell.
         old : /usr/bin/node
         new : /usr/local/bin/node
If "node --version" shows the old version then start a new shell, or reset the location hash with:
hash -r  (for bash, zsh, ash, dash, and ksh)
rehash   (for csh and tcsh)
root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1# node -v
v12.22.9
root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1# ls /usr/local/n/versions/node/18.12.1
bin  CHANGELOG.md  include  lib  LICENSE  README.md  share
root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1# ls /usr/local/n/versions/node/18.12.1/bin/node -v
/usr/local/n/versions/node/18.12.1/bin/node
root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1#  /usr/local/n/versions/node/18.12.1/bin/node -v
v18.12.1
root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1# vim /etc/profile
root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1# source !$
source /etc/profile
root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1# node -v
v18.12.1


sudo npm install -g n

sudo n stable # latest #(升级node.js到最新版) stable #（升级node.js到最新稳定版）


root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1# vim /etc/profile
root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1# !source 
source /etc/profile 
root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1# node -v
v18.12.1
root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1# npm -v
8.19.2
root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1# which npm 
/usr/local/n/versions/node/18.12.1/bin//npm
root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1# which node
/usr/local/n/versions/node/18.12.1/bin//node
root@l-virtual-machine:/home/l/桌面/markdown1/gitbook1# tail -2 /etc/profile
# node
export PATH=/usr/local/n/versions/node/18.12.1/bin/:$PATH



n 显示已安装的Node版本
n latest 安装最新版本Node
n stable 安装最新稳定版Node
n lts 安装最新长期维护版(lts)Node
n version 根据提供的版本号安装Node


```

### 操作

```
1）在<head>中设置幻灯片的主题。
2）在<section>中编写幻灯片的内容。
3）在Reveal.initialize（{});中添加reveal.js的依赖和配置。


使用Markdown编写幻灯片
reveal.js使用Markdown编写幻灯片有两种方式。
1）在HTML文件中直接使用Markdown编写。
2）在HTML文件中引用外部的Markdown文件

如果在HTML文件中直接使用Markdown编写，则需要给<section>标
签 添 加 data-markdown 属 性 ， 并 且 内 容 要 使 用 <textareadata-template>包裹

如果在HTML文件中引用外部的Markdown文件，则需要指定分页的
匹配规则，

data-separator="\n\n\n" 
data-separator-vertical="\n\n"
data-separator-notes="^Note:"
data-charset="utf-8"

导入外部的md文件
<section data-markdown="test.md" data-separator="\n\n\n" 
			data-separator-vertical="\n\n"
			data-separator-notes="^Note:"
			data-charset="utf-8">
			
</section>			

```

### js错误

```
markdown.js:7 Not allowed to load local resource: file:///C:/Users/l/Desktop/vscode/test.md


```

### 添加reveal.js的依赖和配置

```
 在Reveal.initialize({});中进行对reveal.js的配置，如开启历 史记录、显示页面、设置全局转场效果等，
 
 <script src="dist/reveal.js"></script>
	<script src="plugin/notes/notes.js"></script>
	<script src="plugin/markdown/markdown.js"></script>
	<script src="plugin/highlight/highlight.js"></script>
	<script src="plugin/math/math.js"></script>
	<script src="plugin/search/search.js"></script>
	<script src="plugin/zoom/zoom.js"></script>
	
 Reveal.initialize({
			hash: true,
			history: true, // 开启历史记录
			slideNumber: true, // 显示页码
			transition: "convex", // 转场效果
			// Learn about plugins: https://revealjs.com/plugins/
			plugins: [RevealMarkdown, RevealHighlight, RevealNotes]
		});
		
		
test:
plugins: [{
	src: "x.js" , async: true , 
}]

关于配置依赖的库的语法解读如下。
1）src：指定要加载的脚本的路径。
2）async：[可选]，如果脚本要在reveal.js启动后加载，则设为
true，默认为false。
3）callback：[可选]，指定脚本加载后要执行的函数

更 多 配 置 请 参 考 https://github.com/denehyg/reveal.js-toolbar

```

## markdown 工具

### onenote

```
OneNote本身并不直接支持Markdown，但如果想在OneNote中使用
Markdown，可以通过插件来实现。
插 件 下 载 地 址 ： https://www.onenotegem.com/onemarkdown.html，目前只支持Windows版本。

```

### Online-Markdown

```
打开https://www.flyzy2005.cn/tools/online-markdown/进入在
线编辑页面，可以根据个人喜好调整页面主题和代码主题，还可以实
时预览渲染效果
复制渲染后的内容，粘贴到微信公众号的编辑器中，原有的文档
格式会得以保持，


```

### Md2All

```
Md2All的使用方法跟Online-Markdown差不多，只不过多了一个下
载HTML文档的功能。
Md2All地址为http://md.aclickall.com/
```

### MkDocs

```
MkDocs是一款用Python开发的静态站点生成器，它可以快速地创 建项目文档。文档的源码使用Markdown编写，配置文件使用YAML编 写，能够一键编译成静态站点
```

### VuePress

```
VuePress是一个比较新的静态网站生成器，主要用于编写技术文
档。它集各家之所长，提供了在Markdown文件中使用Vue组件的功能，
集成了Google Analytics，以及基于Git的“最后更新时间”功能。
VuePress 有 完 整 的 中 文 指 南 ， 网 址 为 ：
https://vuepress.vuejs.org/zh/guide/。
```

### hexo

```
Hexo是一个快速、简洁且高效的博客框架工具。它可以把
Markdown文档快速解析成静态页面，并支持各种漂亮的主题。所以我
们可以使用熟悉的Markdown来写文章（编辑器可以随便选），然后通
过Hexo把文章转换成静态页面，再把这些静态页面托管到GitHub上，
然后绑定一个自己喜欢的域名，个人博客就搭建完成了

GitHub Pages 旨在托管来自 GitHub 存储库的个人、组织或项目页面。
```

### 如何使用Hexo+GitHub Page来搭建个人博

```
cnpm install hexo-cli -g
hexo init myblog 
cd myblog 
npm install 
生成静态网站
hexo g 生成项目文档
hexo s 启动服务

---
lizejun1234.github.io
https://github.com/LIZEJU/lizejun1234.github.io
echo "# lizejun1234.github.io" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/LIZEJU/lizejun1234.github.io.git
git push -u origin main

http://lizejun1234.github.io/


  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

git config --global user.name "m18611694189@163.com"
git config --global user.email "m18611694189@163.com"
lizejun1234Q@

npm install hexo-deployer-git --save

hexo new "My New Post" 创建一篇文章
INFO  Created: ~/桌面/markdown1/myblog/source/_posts/My-New-Post.md 生成的文章的路径


命令简写
hexo n "我的博客" == hexo new "我的博客" #新建文章
hexo g == hexo generate #生成
hexo s == hexo server #启动服务预览
hexo d == hexo deploy #部署

hexo server #Hexo会监视文件变动并自动更新，无须重启服务器
hexo server -s #静态模式
hexo server -p 5000 #更改端口
hexo server -i 192.168.1.1 #自定义 IP
hexo clean #清除缓存，若是网页正常情况下可以忽略这条命令


http://lizejun.github.io/


deploy:
  type: git
  repo: https://github.com/LIZEJU/LIZEJUN.github.io.git
  branch: main
  ##repo: https://github.com/LIZEJU/lizejun1234.github.io.git
  ##repo: git@github.com:LIZEJU/lizejun1234.github.io.git
	
  ##token: "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"
  ##name: m18611694189@163.com
  ##email: m18611694189@163.com

  #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

  
  
  
```

### 创建GitHub Pages

```
GitHub Pages是一个静态网站托管服务工具，很多人使用GitHub
Pages来搭建博客

STEP 1，在GitHub上创建一个仓库。
打开https://github.com/new，在【Repository name】框中输入
[username.github.io]，然后单击【Create repository】创建一个新
的仓库。

目前仓库中还没有内容，当我们把静态网站推送到GitHub之后，
就可以通过http://bxiaopeng.github.io/来访问网站了

STEP 2，把Hexo生成的静态网站推送到GitHub上。
首先，修改_config.xml，示例如下

deploy:
	type: git
	repo: xx.git
	branch: master
	
部署
hexo d 执行部署命令
如果出现错误
cnpm install hexo-deployer-git --save

hexo d 

注意： 现在博客的访问地址是github.io的子域名，并不是你自
己的独立域名。独立域名相当于个人名片，使用独立域名更便于记
忆，它的注册申请很简单，这里不再赘述。下面我们以阿里云为例，
介绍如何绑定自己的域名


ssh-keygen -t ed25519 -C "m18611694189@163.com"

无文件要提交，干净的工作区
Username for 'https://github.com': m18611694189@163.com	
Password for 'https://m18611694189@163.com@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: 'https://github.com/LIZEJU/lizejun1234.github.io.git/' 鉴权失败
FATAL Something's wrong. Maybe you can find the solution here: https://hexo.io/docs/troubleshooting.html
Error: Spawn failed
    at ChildProcess.<anonymous> (/home/l/桌面/markdown1/myblog/node_modules/hexo-util/lib/spawn.js:51:21)
    at ChildProcess.emit (events.js:314:20)
    at Process.ChildProcess._handle.onexit (internal/child_process.js:276:12)
   

ssh: connect to host github.com port 22: Connection refused

ssh-keygen -t rsa -C "m18611694189@163.com"


error: 源引用规格 master 没有匹配

git config --global user.name "m18611694189@163.com"

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


/myblog# git push  origin main
Username for 'https://github.com': m18611694189@163.com
Password for 'https://m18611694189@163.com@github.com': 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

remote: Permission to LIZEJU/lizejun1234.github.io.git denied to LIZEJU.
fatal: 无法访问 'https://github.com/LIZEJU/lizejun1234.github.io.git/'：The requested URL returned error: 403

修改 Personal access tokens 权限

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

访问地址
https://lizeju.github.io/lizejun.github.io/

通过自定义域名实现访问，解决这个
cutom.com ---> lizeju.github.io/lizejun.github.io/

以后不用设置github.io , 仓库名自定义设置

仓库名称：hexo_blog
访问首页的地址：https://lizeju.github.io/hexo_blog/

配置文件： _config.yaml
# URL
## Set your site url here. For example, if you use GitHub Page, set url as 'https://username.github.io/project'
url: https://lizeju.github.io/hexo_blog/
deploy:
  type: git
  repo: https://github.com/LIZEJU/hexo_blog.git
  branch: main
  
# Extensions
## Plugins: https://hexo.io/plugins/
## Themes: https://hexo.io/themes/


```

![image-20221216083708719](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221216083708719.png)

![image-20221216083852484](C:%5CUsers%5Cl%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20221216083852484.png)

### 域名解析

```
登录阿里云→进入【控制台】→进入【域名】→选择【域名列
表】→在【全部域名】中单击你的域名→进入域名基本信息页面→单
击【域名解析】进入域名解析页面，

```

### hexo主题nexT

```
NexT是一款非常流行的主题，下面我们就以NexT为例，介绍如何
安装和使用Hexo主题。其项目地址为https://github.com/theme-next/hexo-theme-next。

git clone x 
cd 
git tag -l

git checkout tags/v6.0.1
修改config.xml 配置theme:hexo-theme-next 
hexo g --debug 
hexo s --debug 

git clone https://github.com/LIZEJU/hexo-theme-next.git
git checkout tags/v6.0.1
```

## gitbook

```
小提示： 本书所提及的GitBook在没有特殊说明的情况下，均是
指GitBook 命令行工具。由于www.gitbook.com在国内访问体验较差，
因此不多作介绍

几点优势。
1）支持Markdown和AsciiDoc语法。
2）支持多语言，支持变量、模板和模板继承。
3）可以导出静态站点或电子书（支持PDF、ePub、mobi等格
式）。
4）有丰富的插件。
5）可以使用Git管理写作内容，方便多人协作和版本管理。
6）可以将内容托管在GitHub或Gitlab中


```

### 环境配置

```
cnpm install gitbook-cli -g

npm install gitbook-cli -g

mkdir mygitbook
cd mygitbook
gitbook init  生成summary.md readme.md文件 readme简介 summary.md目录
gitbook serve 启动服务
执行gitbook serve命令后，会先执行gitbook build编译书籍，
如果编译没有问题，就会打开一个Web服务器，默认监听4000端口。如
果编译有问题，则会抛出错误信息。
第4步：查看效果，用浏览器打开http://localhost:4000/查看书
籍站点的显示效果，如下图所示


```

### 实践

```
写作工具组合是：GitBook（书籍管理）+Typora（编
辑器）+SourceTree（版本控制），对于编写和管理电子书来说，这是
一种非常高效的组合。当然，使用VS Code也是一个不错的选择。

gitbook pdf ./ ./x.pdf 

如果想要开源，可以把书籍托管到GitHub上，然后绑定自己的域
名 。 一 个 比 较 好 的 例 子 是
https://github.com/rootsongjc/kubernetes-handbook。


GitBook 官 方 提 供 了 一 个 完 整 的 例 子
（https://github.com/GitbookIO/git），

gitbook build 

gitbook init 
TypeError: cb.apply is not a function

---
nvm install 10.14.1
nvm use 10.14.1

n 10.14.1

 installing : node-v10.14.1
       mkdir : /usr/local/n/versions/node/10.14.1
       fetch : https://nodejs.org/dist/v10.14.1/node-v10.14.1-linux-x64.tar.xz
       
这个没有解决
---
vim /usr/local/n/versions/node/18.12.1/lib/node_modules/cnpm/node_modules/graceful-fs/polyfills.js

// fs.stat = statFix(fs.stat)
// fs.fstat = statFix(fs.fstat)
// fs.lstat = statFix(fs.lstat)
注释这三行

/usr/local/n/versions/node/18.12.1/lib/node_modules/gitbook-cli/node_modules/_npm@5.1.0@npm/node_modules/graceful-fs/polyfills.js:287
      if (cb) cb.apply(this, arguments)
                 ^

TypeError: cb.apply is not a function
    at /usr/local/n/versions/node/18.12.1/lib/node_modules/gitbook-cli/node_modules/_npm@5.1.0@npm/node_modules/graceful-fs/polyfills.js:287:18
    at FSReqCallback.oncomplete (node:fs:208:5)

Node.js v18.12.1

vim  /usr/local/n/versions/node/18.12.1/lib/node_modules/gitbook-cli/node_modules/_npm@5.1.0@npm/node_modules/graceful-fs/polyfills.js





```

### gitbook pdf转换

```
PS C:\Users\l\Desktop\vscode\gitbooktest> gitbook pdf ./ ./1.pdf
info: 7 plugins are installed 
info: 6 explicitly listed 
info: loading plugin "highlight"... OK 
info: loading plugin "search"... OK 
info: loading plugin "lunr"... OK 
info: loading plugin "sharing"... OK 
info: loading plugin "fontsettings"... OK
info: loading plugin "theme-default"... OK 
info: found 3 pages 
info: found 2 asset files 
error: error while generating page "doc/hexo +github pages搭建个人博客.md": 

Error: Invalid URI "c:/Users/l/AppData/Roaming/Typora/typora-user-images/image-20221217040514308.png"


md文件中的图片文件uri地址无效

```

### gitbook插件

```
gitbook install gitbook-plugin-atoc


```

### gitbook和github仓库互相同步

```
gitbook 使用github账户登录

gitook创建一个space空间，然后sync同步github某一个仓库
可以从gitbook到github,也可以从github到gitbook
```

## 怎样制定学习计划

```
怎样制定一个高效学习计划
制定一个你想要实现的广泛的目标，比如：考上重点大学。 然后创建一些具体目标，具体日期来实现这些目标。 ...
评价你的现实，看看你已经达到了什么程度。 ...
弄清楚你将如何达到自己的目标。 ...
一段时间（如一个星期）后，评估你的计划是否成功。 ...
让自己有动力。

目标
评价当前的自己处于什么位置
如何实现目标，与目标的距离
隔断时间评价自己
鼓励自己
```

## ubuntu通过v2ray实现终端上网

```
wget https://github.com/v2fly/v2ray-core/releases/download/v4.31.0/v2ray-linux-64.zip
unzip x.zip -d directory
config.json 
 
./v2ray --config config2.json 
V2Ray 4.31.0 (V2Fly, a community-driven edition of V2Ray.) Custom (go1.15.2 linux/amd64)
A unified platform for anti-censorship.
2022/12/16 07:32:49 [Info] v2ray.com/core/app/dns: DNS: created localhost client
2022/12/16 07:32:49 [Info] v2ray.com/core/common/platform/ctlcmd: <v2ctl message> 
v2ctl> Read config:  config2.json
2022/12/16 07:32:49 [Info] v2ray.com/core/transport/internet/tcp: listening TCP on 127.0.0.1:1080
2022/12/16 07:32:49 [Info] v2ray.com/core/transport/internet/udp: listening UDP on 127.0.0.1:1080
2022/12/16 07:32:49 [Info] v2ray.com/core/transport/internet/tcp: listening TCP on 127.0.0.1:1087
2022/12/16 07:32:49 [Warning] v2ray.com/core: V2Ray 4.31.0 started


# ss -ntlp|grep 108
LISTEN 0      4096       127.0.0.1:1087      0.0.0.0:*    users:(("v2ray",pid=33984,fd=8))         
LISTEN 0      4096       127.0.0.1:1080      0.0.0.0:*    users:(("v2ray",pid=33984,fd=3))         


export ALL_PROXY=socks5://127.0.0.1:1080
export http_proxy=http://127.0.0.1:1081
```
