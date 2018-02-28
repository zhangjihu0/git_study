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
```
## linux 命令
- pwd print working directory
- rm -rf 文件夹 删除文件
- rm 文件名
- mkdir git-project 创建文件
- cd git-project/ 改变目录
- ls -al 显示目录下所有的文件包含隐藏文件
- touch 1.txt 创建空文件1.txt
- cat 1.txt 查看文件内容




