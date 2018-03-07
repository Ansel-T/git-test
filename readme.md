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
