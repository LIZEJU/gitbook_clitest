# gitbook-cli上传静态页面

### 脚本1

```
#!/bin/bash


export ALL_PROXY=socks5://127.0.0.1:1080
export http_proxy=http://127.0.0.1:1087
source /etc/profile
#export PATH=/usr/local/n/versions/node/18.12.1/bin/:$PATH


path1="/home/l/桌面/markdown1/gitest/gitbook_clitest"

cd $path1

echo `pwd`


git checkout test 

git pull 

ls *.md

gitbook build 

git checkout p1 
cp -r _book/* .
git add .
git commit -m "1"
git push origin p1
```

### 脚本2

```
#!/bin/bash

# 设置终端代理，在当前终端窗口有用，或者当前脚本有用
export ALL_PROXY=socks5://127.0.0.1:1080
export http_proxy=http://127.0.0.1:1087
# 激活环境变量
source /etc/profile
#export PATH=/usr/local/n/versions/node/18.12.1/bin/:$PATH

# 为了可以少写几遍 github username password(person token)
git config credential.helper store
# 文档的路径
path1="/home/l/桌面/markdown1/gitest/k8s2"

cd $path1

echo `pwd`

# git切换到main主分支
git checkout main

git fetch --all

git reset --hard origin/main
# 更新本地为最新的文档
git pull 

#git push -u origin main
sleep 10
# 写上传github仓库忽略的文件
cat >>.gitignore<<EOF
*~
_book
.DS_Store
EOF
# gitbook 生成静态文件
gitbook build 
# 上传到仓库
git add .
git commit -m "main"
git push -u origin main 
# 切换到分支pages
git checkout pages

cat >>.gitignore<<EOF
*~
_book
.DS_Store
EOF

# 将静态文件移动到根目录
cp -r _book/* .
# 上传
git add .
git commit -m "1"
git push origin pages


```
