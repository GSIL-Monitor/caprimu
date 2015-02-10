#git 常用操作
##常用操作
1. 分支 改动的内容

	`git show 12e665b28`
	
2. 撒销一个合并

	如果你觉得你合并后的状态是一团乱麻，想把当前的修改都放弃，你可以用下面的命令回到合并之前的状态：

	`git reset --hard HEAD`

	或者你已经把合并后的代码提交，但还是想把它们撒销：

	`git reset --hard ORIG_HEAD`

3. 分支修改过的文件

	`git diff master --name-only `
4. “强制”的将改动推到远程：

	`git reset --hard 34eqfds`

	`git push origin master --force` or  `git push origin +master	`