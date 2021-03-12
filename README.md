# how to learn git fastly  

简易的命令行入门教程:
## Git 全局设置:
```powershell
git config --global user.name dawson
```

```powershell
git config --global 1074716097@qq.com
```

查看git配置信息：`git config --list`  
## 创建本地git仓库:
mkdir git-demo-study
cd git-demo-study

```powershell
git init
```

写内容：learn README.md

```powershell
git commit -m "first commit"
```
## 推送到远程github仓库:
~~*繁琐操作命令：*~~ git push	https://github.com/yanqisheng/git-demo-study.git	master

改地址名字，默认 origin：
```powershell
git	remote	add	origin	https://github.com/yanqisheng/git-demo-study.git
```
如果想要更简便，git push -u 远程仓库地址别名 分支名称。`-u 记住推送地址及分支，下次推送只需要输入git push即可`

```powershell
git push -u origin master
git push
```
## 拉取远程github仓库
- 初次拉取
```powershell
git clone 仓库地址
```
- 本地已有仓库？

```powershell
git pull 远程仓库地址 分支名称
```
