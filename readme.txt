Git 是一个版本控制软件
Git  是一个免费软件

Test branch:
Git鼓励大量使用分支：

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>或者git switch <name>

创建+切换分支：git checkout -b <name>或者git switch -c <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>

<<<<<<< HEAD
test
=======
用git log --graph命令可以看到分支合并图。
>>>>>>> featurel
