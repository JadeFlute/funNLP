

## git
### 关联上游仓库并更新

```
# 执行一次就行
git remote add upstream https://github.com/JadeFlute/funNLP.git
git remote -v


# 将upstream-master分支的代码合并到当前分支
git fetch upstream
git checkout master
git merge upstream/master



```






