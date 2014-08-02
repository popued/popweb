#POPUED team web

------

*项目下载*
>$git clone https://github.com/popued/popweb.git

*项目本地运行*
>cd popweb  
$hexo generate  
$hexo server  

*项目提交*  
>$hexo clean  
$git add "修改或新建文件路径"  
$git commit -m "文件描述"  
$git push origin master

*项目更新*  
>$git pull origin master 

*项目部署到github.io*
>$git clone https://github.com/popued/popued.github.io.git  
$hexo g  
然后生成的所有public文件粘贴覆盖popued.github.io的所有文件  
cd popued.github.io  
$git add .  
$git commit -m "提交描述"  
$git push origin master

*项目提示*
>每次要更新代码之前先$git pull 一下