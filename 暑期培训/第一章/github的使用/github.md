# github的使用
>我的仓库地址：https://github.com/YYTAshely/Waste-repository.git
### 浏览GitHub，使用GitHub高级搜索功能，找到几个你感兴趣的仓库，并阅读其README介绍，了解该仓库。
- 找了找工作室的仓库，结果发现不是公开的
### 尝试发布任务一所创建的本地仓库到GitHub
- 在github中创造一个自己的仓库
- 按照github的指示将代码复制到任务一的命令窗口中
- 
*在push我的文件时，出现了ssl证书问题，在终端中输入git config http.sslVerify false (此方法法不太安全）*
### 为你上传到GitHub上的仓库提出一个issue
- 在issue界面点击new issue
- 输入标题，内容最后提交就可以了
### 为你上传到GitHub上的仓库提交一个pr
- 由于本地仓库已经连上我的仓库了，就不再进行git remote add upstream操作
- 使用git checkout -b yyt,创造一个yyt的分支，然后对项目的修改就可以在这个分支上进行
- 修改完成之后上传提交
- 最后输入git push -u origin yyt,将修改后的分支push上去
- 回到我们的仓库，点击分支，就可以看到刚才的提交
- 点击pull request ，再点new pull request ,选择我们的分支，点击create pull request ,再填写pr的相关信息，就欧克了
### 为你上传到GitHub上的仓库合并一个pr
- 在pr中选择我们刚才提交的pr，点击“Merge pull request”按钮，然后点击“Confirm merge”完成合并。
