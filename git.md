#使用代理前缀
git clone -c https.proxy=http://127.0.0.1:1080 地址

git init

git add *

git commit -m "wrote git readme file"



版本记录
git log --pretty=oneline
或者 git reflog
#版本回退
git reset --hard c234

#添加远程仓库，Permission denied (publickey)，需要更新ssh。
git remote add origin git@github.com:shioyim/commond.git

git push -u origin master


#删除文件夹带参数r,记得commit
git rm 文件名
