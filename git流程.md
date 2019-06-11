# git命令学习

标签（空格分隔）： jobnote

---

![git原理图](http://m.qpic.cn/psb?/V11Rhu0F083yyH/fhZMNzaivI.S3LXpJsGewaUKkOmiCiQ9Yl7LA67qGDg!/b/dMAAAAAAAAAA&bo=lARUAZQEVAERCT4!&rf=viewer_4)

## 基本流程
### 1. git init
> 初始化一个仓库

### 2. git clone 网址
> 克隆一个项目

### 3. git status
> 查看当前状态

### 4. git pull
> 拉取远程仓库最新的版本

### 5. git add .
> 增加修改到文件

### 6. git commit -m '注释'
> 提交到本地仓库

### 7. git push
> 提交到远程仓库

## 进阶流程
### 1. git log --oneline
> 查看日志，每个版本一行显示

### 2. git branch -l
> 查看所有分支

### 3. git branch -b  dev
> 删除dev分支

### 4. git checkout -b dev
> 新建并且切换到dev分支

### 5. git stash
> 保存当前修改到缓存中

### 6. git checkout master
> 切换到master分支

### 7. git stash pop
> 把缓存中的修改抛出

### 8. git reset --hard HEAD^ 
> 版本回退到上一个版本

### 9. git reflog
> 查看查看所有分支的所有操作记录

### 10. git reset --hard 版本号
> 版本回退到某一个版本

## 高级操作
### 1. git cherry-pick 版本号
> 可以选择某一个分支中的一个或几个commit(s)来进行操作,对已经存在的commit 进行再次提交.
