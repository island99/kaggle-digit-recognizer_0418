
## day one

理解git中 *工作区* ， *版本库* ，以及版本库中的 *暂存区* 、 *分支* 、 和指针 *HEAD*。

*origin* 一般是默认远程库，`git push` 把当前分支master推送到远程。

每一次合并其他的分支都需要关联远程库 `git remote add server-name git@server-name:path/repo-name.git`

然后需要注意的就是push之前记得pull一下，不然的话，选择版本解决冲突之后，需要先 `git commit` 一下。


