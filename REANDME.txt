一、将代码提交到远程库
1.代码库的初始化
Git Bash 指定路径到微信小程序代码库
wuzhouxing@wuzhouxing MINGW64 /d/wuzhouxing/SourceProject/com.webchat.demo
$ git init  初始化版本库
Initialized empty Git repository in D:/wuzhouxing/SourceProject/com.webchat.demo/.git/

wuzhouxing@wuzhouxing MINGW64 /d/wuzhouxing/SourceProject/com.webchat.demo (master)
$ git add
Nothing specified, nothing added.
Maybe you wanted to say 'git add .'?

wuzhouxing@wuzhouxing MINGW64 /d/wuzhouxing/SourceProject/com.webchat.demo (master)
$ git add .  添加文件到版本库
warning: LF will be replaced by CRLF in app.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app.json.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in app.wxss.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in pages/index/index.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in pages/index/index.wxml.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in pages/index/index.wxss.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in pages/logs/logs.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in pages/logs/logs.json.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in pages/logs/logs.wxml.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in pages/logs/logs.wxss.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in project.config.json.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in utils/util.js.
The file will have its original line endings in your working directory.

wuzhouxing@wuzhouxing MINGW64 /d/wuzhouxing/SourceProject/com.webchat.demo (master)
$ git commit -m "webchat 小程序 first commint"  添加的文件到代码块
[master (root-commit) 2e570ae] webchat 小程序 first commint
 Committer: unknown <wuzhouxing@diag.launch>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 12 files changed, 236 insertions(+)
 create mode 100644 app.js
 create mode 100644 app.json
 create mode 100644 app.wxss
 create mode 100644 pages/index/index.js
 create mode 100644 pages/index/index.wxml
 create mode 100644 pages/index/index.wxss
 create mode 100644 pages/logs/logs.js
 create mode 100644 pages/logs/logs.json
 create mode 100644 pages/logs/logs.wxml
 create mode 100644 pages/logs/logs.wxss
 create mode 100644 project.config.json
 create mode 100644 utils/util.js

 二、代码块提交到远程服务器
 git remote add origin 
 
 git push -
 

