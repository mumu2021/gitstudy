Git is a distributed version control system.
Git is a free software distributed under the GPL.
我再git这里又写了点内容。
git tricks changes of files.
new files
this add new remod
修改修改


git config --global user.name "Mumu"  设置名字
git config --global user.email "Xinglinhe@qq.com"  全局设置邮箱
git init  初始化git
ls -ah 列出目录包括隐藏文件
git add readme.txt  添加readme.txt到工作区
git commit -m "添加备注" 提交工作区 添加备注
pwd  显示当前目录
cd .>file.txt  新建file.txt文件
rm test.txt 删除文件 非git删除
git status 查看当前仓库状态
git diff 查看上次怎么修改的
git log 显示日志  从远到近的日志
git reset --hard HEAD^ 把当前版本回退到上一个版本
git reset --head HEAD^^ 把当前版本回退到上两个版本
git reflog  记录了你的每一次命令
git diff -- readme.txt 查看指定工作区文件和版本库里面的区别
git reset HEAD reamde.txt 吧暂存区的修改撤销  从新放回工作区
git checkout -- reamde.txt
git rm test.txt 从git删除该文件
git -commit -m "del test.txt file"
git checkout是用版本库里的版本替换工作区的版本
git remote add orign git@github.com:Mumu2021/gitstudy.git 在本地关联远程库
git push orign master 把本地master分支的最新修改推送至github


Creating a new branch is quick AND simple.
修改这个文件