git reset HEAD~x --hard(soft,mixed)          x代表回退几个版本   hard强制回滚本地文件 stash head   midxed回滚 文件  stash   soft回退 head

git rebase test  						假如当前分支是master   是将master最近开发节点复制到test开发节点之后 并复制过来
git merge test         					master 和test 上游合并到 test上（三者合并） 并新生成一个commit