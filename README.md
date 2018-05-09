# git学习 #
Git是一个开源的分布式版本控制系统，用于敏捷高效地处理任何或小或大的项目。

Git 是 Linus Torvalds 为了帮助管理 Linux 内核开发而开发的一个开放源码的版本控制软件。

Git 与常用的版本控制工具 CVS, Subversion 等不同，它采用了分布式版本库的方式，不必服务器端软件支持。
## git基本指令 ##
1. git status git仓库当前的状态，比如仓库类的文件有变动或者有新的文件没有加入进来等等
2. git add file/directory 将当前文件保存，但是没有提交，不会生成版本号，
3. git commit -m "description" 提交操作，会生成版本号（随机的），description对这个版本进行描述
4. git log/reflog 查看历史版本信息
5. git reset --hard version 跳转到某个版本
6. git clone url 从远程克隆一个副本到本地
7. git init 初始化一个git仓库

## git 分支管理##
1. git checkout [-b] branchName [remote/branchName] 跳转到某个分支，[-b]创建某个分支  [remote/branchName]远程分支名
2. git branch 查看所有分支
3. git merge branchName 合并分支
4. git branch -d branchName 删除分支，只是本地删除了
5. git push remote branchName 向远程推送当前分支

## github 使用 ##
1. git remote -v 查看所有远程信息
2. git add remote userName url 添加远程并且为这个远程重命名
3. git push remote branchName 向远程推送某个分支
4. git pull remote branchName 与远程进行同步
5. git fetch remote branckName  与远程进行同步
