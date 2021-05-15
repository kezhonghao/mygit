这是第一行文字，ecs进入命令模式，i恢复编辑,命令模式下:wq保存并退出编辑
git add 文件名 保存至缓冲区
git checkout - readme.txt  缓冲区回滚
git commit -m "提交信息" 提交至本地仓库
git diff 查看文件修改的内容
git status 查看版本库
git log 查看修改日志（包括版本号），可以看到最近的三次记录
git log --pretty=oneline  将日志一行显示
git reset --hard HEAD^  回退，几个^回退几次
git reset --hard HEAD~n  回退，n是几回退几次
git reset --hard 版本号  回退，回退至某个版本
create a new branch is quick.
