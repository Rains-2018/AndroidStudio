git简单操作

参考URL: https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/0013743858312764dca7ad6d0754f76aa562e3789478044000

http://www.runoob.com/w3cnote/git-guide.html


1. 创建一个文件夹
	F:\WorkSpace\GitTest	
 
2. 文件夹下创建一个文件
	F:\WorkSpace\GitTest\Readme.txt

3. 选中文件夹\GitTest，右键 点击选中“Git Bash Here”

4. 把该目录变成一个Git的仓库
	 $ git init	

5. 把Readme.txt文件添加到Git仓库
	$ git add readme.txt
 	$ git commit -m "New File to Studio Git"

6.查看仓库状态和差分
	$ git status
	$ git diff readme.txt
7. 有查分需要提交分两步走
	$ git add readme.txt
	$ git commit -m "This is a new mofify test to add something"

8. 将仓库远程同步到GitHub上面，按如下步骤
   a. 创建SSH KEY，一路回车，在C:\Users\Administrator\.ssh ，复制id_rsa.pub的内容
	$ ssh-keygen -t rsa -C "youremail@example.com"
   b. GitHub 上面 setting\SSH\Add new SSH ,title 任意填，KEY中将上面复制的内容张贴。

   c. 同步代码
	$ git remote add origin git@github.com:Rains-2018/AndroidStudio.git
	$ git push -u origin master

9. 本地代码修改同步三步走
   $ git add readme.txt	
   $ git commit -m "New File to Studio Git"
   $ git push -u origin master	

10. 从GitHub拉取代码
    $ git clone git@github.com:Rains-2018/AndroidStudio.git	

11. 从GitHub上更新最新代码
    $ git pull