git checkount -b local	创建本地分支，并切换至本地分支

git stash	隐藏本地更改

git stash pop	还原本地更改

git pull origin [远程分支名]	拉取远程分支代码

git add .	添加所有更改文件

git commit -m "remark"	提交暂存区文件至本地版本库

git merge [分支名]	将指定分支代码合并至当前分支

git push	将本地版本库代码推送至远程版本库

git reflog	查看操作日志

git reset --hard [版本号]	还原至指定版本号

git reset HEAD [文件名]	把文件从暂存区撤销到工作区

git checkout -- [文件名]	把文件还原至修改前状态

git push origin [本地分支名]:[远程分支名]	将本地分支代码提交至远程指定分支

git fetch	项目上新建一个分支test，使用git branch -a看不到该远程分支，使用[git fetch]取回所有分支更新，就能看到该分支

git push origin :[分支名]	删除远程分支

推送本地项目至git
1：建好对应的git仓库
2：本地：git init
3：git add .
4：git commit -m ""
5：git remote add origin ***.git [远程的git仓库地址]
6：git push origin master
