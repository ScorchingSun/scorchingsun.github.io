### 查看所有分支

git branch -a
### 切换到test远程分支到本地为test分支

git checkout -b B#luxiaolei origin/B#luxiaolei
### 切换到本地分支test

git checkout B#luxiaolei

### 提交代码到分支

git add *

git commit -m "xxx"

git push origin B#luxiaolei

### 同步master分支代码到其他分支

1. 切换到master分支

git checkout master
2. 更新远程最新代码

git pull
3. 切换到其他分支

git checkout B#luxiaolei
4. 合并master到分支

git merge master
5. 将其他分支同步的master分支代码push到远程分支

git push origin B#luxiaolei