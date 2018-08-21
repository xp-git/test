hi git  this is a test file;
carlyle x 
update file
add gpl test
update  file file 

git add .        （注：别忘记后面的.，此操作是把文件夹下面的文件都添加进来）

git commit  -m  "提交信息"  （注：“提交信息”里面换成你需要，如“first commit”）

git push -u origin master   


更新代码
第一步：查看当前的git仓库状态，可以使用git status
git status
第二步：更新全部
git add *
第三步：接着输入git commit -m "更新说明"
git commit -m "更新说明"
第四步：先git pull,拉取当前分支最新代码
git pull
第五步：push到远程master分支上
git push origin master
不出意外，打开GitHub已经同步了
