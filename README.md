

git checkout -- file可以丢弃工作区的修改：
git checkout -- file命令中的--很重要，没有--，就变成了“切换到另一个分支”的命令

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>