# gitbook-cli上传静态页面

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
