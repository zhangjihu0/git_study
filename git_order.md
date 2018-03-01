## git配置
```
 git config --list;
 git config --global user.name 'github-name';
 git config --global user.email 'github-email';
```
## git从初始化到git仓库
- 不要在文件下初始化再，一个项目只初始化一次。
```
 工作区是红色，暂存区是绿色 历史区没有颜色
 git init //告诉git 那个文件夹需要被管理;
 git add .提交到暂存区;
 git status 查看git 状态;
 git rm --cached . -r 暂存区递归删除;
 git commit -m 'message' 提交到历史区;
 git log 历史区版本号，用户;
 git diff 工作区和暂存区比较;
 git diff master 工作区和历史区比较;
 git diff --cached 暂存区和历史区比较;
 git checkout . 工作区放弃变更内容到到上次git add .
 git checkout 1.txt 某个文件
 git reset HEAD 文件名 //回到上一个版本的暂存区
 git reset . //回到上一个版本的暂存区
 git history . 2.txt 打印历史纪录到2.txt
 git commit -a -m 'tijiaop' 当文件已经被提交到暂存区之后可以直接从工作区提交到暂存区 -a 表示add
 git log 查看历史区版本号，通过版本号回滚到指定的版本git reset --hard 版本号=》回滚内容直接覆盖暂存区和工作区。
 git log --graph --oneline 显示合并的图谱
 git reset --hard HEAD^ 回到上版本历史区=》暂存区=》工作区
 git reflog 查看所有版本信息
 git branch 分支查看
 git branch dev 创建分支但没有切换
 git checkout dev 切换分支
 git branch -D dev 删除分支(不能删除当前的分支)
 git checkout -b dev //创建并切换
 git stash 暂存分支的修改后可以切换到其他分支 
 git stash pop 缓存出栈
 git merge 分支名 当前分支与分支名合并
 git rm --cached 文件名 删除暂存区文件
```
## merge 解决冲突
- 遇到冲突时只能手动解决冲突 ，留下想要的结果;


## linux 命令
- pwd print working directory
- rm -rf 文件夹 删除文件
- rm 文件名
- mkdir git-project 创建文件
- cd git-project/ 改变目录
- ls -al 显示目录下所有的文件包含隐藏文件
- touch 1.txt 创建空文件1.txt
- cat 1.txt 查看文件内容
- echo hello > 1.txt //输入hello到目标文件覆盖原来的内容若文件不存在，便直接创建带内容的文件。
- echo hello >> 1.txt //追加内容到目标文件





