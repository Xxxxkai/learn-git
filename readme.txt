do you want to drink one dot dot?
one dot dot means a little tea!
wooo~
git add readme.txt      --提交到暂缓区
git commit -m "zhao_"      --把暂缓区的所有内容提交到当前分支
git log --pretty=oneline
git reset --hard HEAD~100
git reset --hard HEAD^
git reset --hard e3b3906
git reflog 记录每一条命令

客户端与服务端生成ssh key
ssh-keygen -t rsa -C "zky@bupt.edu.cn"
如果不需要设置密码 一路enter


#fatal: remote origin already exists.
git remote rm origin
git remote add origin git@github.com:Xxxxkai/learn-git.git
git branch -M main
git push -u origin main
