### git的使用总结

#### 第一次提交到仓库上https://github.com/hqy479992/wechat_shop.git
1.进入需要提交的项目中， git init 变为git可管理的仓库
    git status 查看状态变更的文件

2.暂存到仓库中（暂存区）
    通过git add .可以把项目全部添加到暂存区，
    git status 

3.暂存区添加到本地仓库中
    git commit -m '提交说明'

4.本地仓库和远程仓库关联
    git remote add origin https://github.com/hqy479992/wechat_shop.git

5.将本地库的所有内容推送到远程仓库上 
    远程仓库为空
    git push -u origin master

    不为空
    git push  origin master

