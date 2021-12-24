GIT学习

- 检出项目
git clone "git path"

- 查看所在分支
git branch

- 查看全部分支
git branch -a

- 删除一个分支（不能删除当前所在的分支，必须先check到别的分支）
git branch -D branch/name

- 更新全部（包括分支）
git pull

- 更新线上某一个分支的代码（不能从下往上更新）
git pull origin branch/name

- 检出一个新分支
git checkout -b branch/name

- 从当前分支切换到另外一个分支
git checkout branch/name

- 查看目前分支状态（用于查看有变动的文件）
git status

- 将变更文件添加到缓存区
git add file

- 将所有变更文件直接添加到缓存区
git add -A

- 将缓存区文件提交（add 后必须要进行此步骤）
git commit -m"注释"

- 将分支提交到线上
git push origin branch/name

- 将某个分支合并到当前所在分支（不能从上往下合并）
git merge branch/name

- 查看某两个分支的不同
git diff branch/name1 branch/name2

- 查看某个提交的commit与当前版本的不同
git diff commit/id

- 将当前分支回归到某一个提交的版本
git reset --hard commit/id

- 撤销缓存区提交的文件
git rm file

- 创建版本tag
git tag v1.0
