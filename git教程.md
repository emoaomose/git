## git教程

回退版本内容

​	git log   找到要回退的提交id(一串英文数字id)

​	git reset --hard [提交id]



新的仓库：

git init   初始化本地配置

git config --global user.name "emoammose"   配置config文件

git config --global user.email "2766550594@qq.com" 配置config文件

echo "xxxx" >> README.md    创建说明文件 

git add README.md   添加指定文件到暂缓区

git commit -m "first commit"   将文件进行提交

git branch -M main  创建并切换main分支 （需要将内容提交到哪个分支就切换哪个分支）

git remote add origin https://github.com/emoaomose/Typora.git  添加远程仓库

git push -u origin main   推送到远程仓库



后续推送修改内容：

git remote add origin https://github.com/emoaomose/Typora.git   

git branch -M main

git push -u origin main