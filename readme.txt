#创建本地库
git init 

#把文件添加到仓库
git add readme.txt

#把文件提交到仓库
git commit -m "append GPL"

#仓库当前的状态
git status

#查看修改内容
git diff

#显示从最近到最远的提交日志
git log  

 加上  --pretty=oneline 精简信息


#回退到上一个版本

$ git reset --hard HEAD^ 

git remote add origin git@github.com:815085226/Gavin_wei.git 
$ git add .     #（添加需要提交的内容）
$ git commit -m "填写备注提交信息更新内容"
$ git push -u origin master

git push origin master