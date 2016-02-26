#为你的fork仓库配置remote
- 查看当前remote配置列表
	`git remote -v`
- 添加上游仓库链接
	`git remote add upstream https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git`
- 查看是否配置正确
	`git remote -v`
#同步
- `git fetch upstream`
- `git checkout master`
- `git merge upstream/master`