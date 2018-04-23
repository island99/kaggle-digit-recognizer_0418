
## day one

理解git中 *工作区* ， *版本库* ，以及版本库中的 *暂存区* 、 *分支* 、 和指针 *HEAD*。

*origin* 一般是默认远程库，`git push` 把当前分支master推送到远程。

每一次合并其他的分支都需要关联远程库 `git remote add server-name git@server-name:path/repo-name.git`

然后需要注意的就是push之前记得pull一下，不然的话，选择版本解决冲突之后，需要先 `git commit` 一下。

> 感觉对“版本”的理解还不够深刻。以及 `本地改变 + add -> 改变被放入暂存 + commit -> 修改本地库`, 都是本地行为，只有push 和 pull才是和远程库交互。

## day two

pca和t-sen都是特征表达学习。

我在[Digit Recognizer 经典kernel](https://www.kaggle.com/arthurtok/interactive-intro-to-dimensionality-reduction)看到了三种实现方法, 其中就有pca和t-sen.

对pca在fit之前先要求协方差矩阵, 特征值, 特征向量不是很理解, 找到一个比较通俗的解答 [四层境界理解pca](https://www.zhihu.com/question/36348219/answer/275378672), 不幸的是我看了很多遍也只限于对第二层有些感受. 还有一个[pca](https://stats.stackexchange.com/questions/2691/making-sense-of-principal-component-analysis-eigenvectors-eigenvalues/140579#140579). 


