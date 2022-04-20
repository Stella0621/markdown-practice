# Git的使用方法

```shell
git version
# 查看当前所处路径
pwd

#  查看当前目录下有哪些文件
ls -l

#  回到主目录
cd(cd ..回到上一层)

# 切换目录change directory
cd Desktop

#  创建新目录
mkdir markdown-practice

#  创建新文件
touch README.md

#  输出文件
cat README.md 

#  初始化Git仓库
git init

#  暂存文件的改动
git add README.md

#  生成一次提交，提交已暂存文件的改动
git commit -m "git的使用方法"

#  中断命令
control C

#  添加一个远程仓库地址
git remote add origin https://github.com/Stella0621/markdown-practice.git

#  向远程仓库推送
git push (github master:master  前面是本地分支，后面是远程分支)



```

