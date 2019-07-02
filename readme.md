# git 使用

- 常用命令

```

        git init              初始化本地git仓库
        git config --global user.name "xxx"               配置用户名
        git config --global user.email "xxx@xxx.com"      配置邮件
        git log               查看日志
        git clone [地址]       克隆远程仓库
        git status            查看当前分支下的文件状态
        git add [file] or *   添加到暂存区
        git commit -m [msg]   提交（暂存区中的文件提交到当前分支）
        git branch            查看分支
        git branch [name]     创建分支
        git checkout [name]   切换分支
        git merge [name]      合并分支  [name]分支合并到当前分支
        git branch -d [name]  删除分支
        git push 远程仓库地址 --delete [分支名称]           删除远程分支

```

# 解决合并分支冲突

# 解决往github上提交代码成功，格子不高亮

往github上提交代码成功后，进入github上可以看到提交的代码，但是却一直没有显示绿点，是因为本地Git的配置邮箱和github上面的邮箱不一致。

- 查看本地邮箱

```
git config user.email

```

得到你本地配置的邮箱，如果和你GitHub上的邮箱不一致，修改一下

- 更改本地邮箱配置

```
git config –global user.email [email] 

```

和Github上保持一致

- 再次提交代码查看，格子就高亮显示。

# 查看和修改远程地址

- git remote -v 

```shell
git remote -v 
```

- git remote set-url origin \[newUrl\]

```shell
git remote set-rul origin https://github.com/*****/***
```



