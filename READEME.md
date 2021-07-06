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
#### 第二次更新文件提交到仓库

1.进入提交的文件夹中，git add . 或者 git add xxx具体文件名
2.git commit -m '提交说明'
3. 拉取远程仓库代码，更新代码
    git pull 
4.git push -u origin master  / git push origin master


#### 创建分支上传

1.创建
    git branch dev
2.切换分支
    git checkout dev
3.关联分支
    git remote add 
4.将分支上传
    git push origin dev