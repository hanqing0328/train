# git 用法

step1: git init

step2: git add .  / git filename 

step3: git status

step4: git config --global user.email "yourmail"

step5: git config --global user.name "yourname"   

// fatal  严重错误

// 账号信息被储存在 gitconfig文件里面

step6: git commit -m "message"   / git commit -a -m "message"

step7: git log ==> 查询提交状态

// git diff ==> 文件更改后查寻，与上一个版本的差异

//git checkout IDnumber ==>查看之前版本

//git log ==> 之前版本后只能查看一个记录

//git checkout master ==> 回到最末版本

//编辑器里推出 :wq

//copy sublimefile fullname paste to editor(gitconfig)

//git config --global alias.st status

//git config --global alias.br branch      ====>  alias取别名

//git config --global alias.co checkout

//git config --global alias.ci commit





# GitHub 上传方法

step1: github创建一个新的远程仓库 new repository

step2: git remote add origin 仓库地址

step3: git push origin master

step4: 又一次改变后 git ci -a -m "filename"

step5: git push -u origin master ===>-u总是上传到的意思，下次运行只要写 git push就可以了 

step6: git pull ==>如果线上和线下两边都改变需要合并时

// git clone github仓库地址



# GitHub 文件共享方法

step1: github创建以用户名为名的仓库Repository name: username.github.io

step2: 把本地文档上传到仓库
