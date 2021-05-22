### 下载代码

```shell
git clone [-b <分支名称>] <git远程路径> [<本地路径>]
```

### 查看所有分支

```shell
git branch -a
```

### 切换到test远程分支到本地为test分支

```shell
git checkout -b B#luxiaolei origin/B#luxiaolei
```

### 切换到本地分支test

```shell
git checkout B#luxiaolei
```

### 提交代码到分支

```shell
git add *
git commit -m "xxx"
git push origin B#luxiaolei
```

### 同步master分支代码到其他分支

#### 1. 切换到master分支

```shell
git checkout master
```

#### 2. 更新远程最新代码

```shell
git pull
```

#### 3. 切换到其他分支

```shell
git checkout B#luxiaolei
```

#### 4. 合并master到分支

```shell
git merge master
```

#### 5. 将其他分支同步的master分支代码push到远程分支

```shell
git push origin B#luxiaolei
```

