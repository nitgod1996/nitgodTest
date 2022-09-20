![img](git%E5%91%BD%E4%BB%A4%E7%AE%80%E4%BB%8B/git-command.jpg)

**说明：**

- `workspace`：工作区
- `staging area`：暂存区/缓存区
- `local repository`：版本库或本地仓库
- `remote repository`：远程仓库

**命令简介**

* `git add`：将变动的文件及内容添加到暂存区（Index），它像个缓存区域，临时保存你的改动
  * `git add <filename>`：添加指定文件到暂存区
  * `git add .`：添加当前目录下的**所有文件**到暂存区
* `git commit`：（生成快照）将暂存区内容添加到**本地仓库**中。
  * `git commit -m [message]`：添加时带上备注信息
  * `git commit [file1] [file2] ... -m [message]`：只添加指定的文件到本地仓库
  * `git commit -a`：不需要`git add`直接提交到本地仓库
* 