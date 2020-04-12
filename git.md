## Git
## 1.Git配置
+ git config --global user.name "eesuu2598"   [user.name=github.name]
+ git config --global user.email "1252554292@qq.com"
## 2.查看状态
+ git status
## 3.提交
+ git add <filename>   [.全部 a 没有追踪过的文件不会提交]
## 4.显示修改
+ git diff       
## 5.撤回修改
+ git reset  
## 6.显示配置信息
+ git config --list
## 7.打开编辑器修改
+ git commit <enter>   [打开编辑器 vim/nvim 保存退出后 会自动提交]
## 8.设置默认编辑器
+ git config --global core.eduitor vim/nvim
## 9.git忽略文件
+ vim .gitignore       [mkcd .gitignore  vim .gitignore 写入被git忽略文件的文件名]
## 10.停止追踪
+ git rm --cached <filename>  [停止追踪]

## Git分支
## 1.新建分支
+ git branch <branchname>    
## 2.进入分支
+ git checkout <branch>
## 3.切换分支
+ git checkout master
## 4.合并分支
+ git merge <filename>
## 5.删除分支
+ git -d <filename>              [不会删除为提交的文件]
## 6.强制删除
+ git -D <filename>              [强制删除 会删除未提交的文件]
## 7.查看分支
+ git branch

