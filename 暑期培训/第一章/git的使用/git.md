# git的版本管理
## a. git add
- 使用vscode打开指定文件text.txt,然后打开终端
- 输入git.init,在当前目录创造一个本地仓库
- 输入git.add text.txt,将该文件放到暂存区，或者用git.add .将当前目录所有文件放到暂存区
## b. git commit
- 输入git.commit -m"在此写上提交说明",这样就完成提交了
## c. 回退到某次提交
- 输入git log,打开日志，查找要回退的提交id
- 输入git reset --hard 这里写上提交id
> hard会删除之前的记录，还有soft和mix的用法，在此懒得说明
## d.创建分支
- 输入git checkout -b 在此输入分支名，这样就创建好了一个分支了
## e.删除分支
- 输入git checkout -d 在此输入要删除的分支名，这样就删除了
## f.回退某个文件
- 点击某个文件，对它进行修改
- 在命令窗口输入git restore,就取消修改了
## g.合并分支
- 输入git checkout master，回到master分支
- 输入git merge 在此输入要合并的分支，合并完成
