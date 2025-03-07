# solid-winner
test my first repository
#git 测试

git clone 仓库的url --将远程仓库内容克隆到本地文件夹  隐藏文件夹.git是本地仓库 本地文件夹下除了.git文件夹以外的所有文件是文件系统
git add 文件名.后缀 --将工作目录下的目标文件添加到暂存区
git commit --将暂存区的文件上传到本地仓库
git push --将本地仓库的文件上传到远程仓库
git pull --将远程仓库的文件下载到工作目录

git init 仓库名称 
cd 仓库名称 --bash转到仓库
touch 文件名 --工作目录（未跟踪）
git status --查看仓库状态 Untracked files：不受控制  Changes to be committed:在暂存区待提交  Changes not staged for commit:
git add . --将工作目录所有文件提交到暂存区（已跟踪）；在暂存区使用git rm --cached可以把暂存区清空（未跟踪）
git add 文件名 --将工作目录指定文件提交到暂存区（已跟踪）
git commit -m '提交到暂存区时的注释'
vi init --进入vi编辑器对init文件进行编辑，编辑后需要add到暂存区
git diff --查看工作目录和暂存区的差别
git diff --cached --查看暂存区和本地仓库的差别
git diff HEAD --查看工作目录和本地仓库的差别
