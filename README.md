#git 通用操作

### 下载安装
>*检查更新*
> apt update 

>*安装指令*
>apt-get install git

### 配置用户信息
>*配置用户名*
>git config -global user.name [name]

>*配置用户邮箱*
>git config -global user.email [email@.com]

>*配置编译器*
>git config core.editor pycharm

>*查看配置信息*
>git config  \--list

### 基本操作
>*初始化仓库*
>git init

>*查看仓库状态*
>git status

>*将工作区内容记录到暂存区*
>git add [files..]  / git add .

>*将文件同步到本地仓库*
>git commit -m [message]

>*查看日志文件*
>git log
>git log \--pretty=oneline

>*移动文件*
>git mv [file] [path]

>*删除文件*
>git rm [file]

>*恢复文件*
>git checkout [commit_id] [file]

### 远程上传和下载
>*增加远程仓库*
>git remote add [origin] [远程端地址:https://github.com/xxx]

>*将本地分支文件上传*
>git push -u [origin] [master]
>***输入git账户和密码***

>*远程下载*
>git pull













