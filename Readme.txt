git�򵥲���

�ο�URL: https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/0013743858312764dca7ad6d0754f76aa562e3789478044000

http://www.runoob.com/w3cnote/git-guide.html


1. ����һ���ļ���
	F:\WorkSpace\GitTest	
 
2. �ļ����´���һ���ļ�
	F:\WorkSpace\GitTest\Readme.txt

3. ѡ���ļ���\GitTest���Ҽ� ���ѡ�С�Git Bash Here��

4. �Ѹ�Ŀ¼���һ��Git�Ĳֿ�
	 $ git init	

5. ��Readme.txt�ļ���ӵ�Git�ֿ�
	$ git add readme.txt
 	$ git commit -m "New File to Studio Git"

6.�鿴�ֿ�״̬�Ͳ��
	$ git status
	$ git diff readme.txt
7. �в����Ҫ�ύ��������
	$ git add readme.txt
	$ git commit -m "This is a new mofify test to add something"

8. ���ֿ�Զ��ͬ����GitHub���棬�����²���
   a. ����SSH KEY��һ·�س�����C:\Users\Administrator\.ssh ������id_rsa.pub������
	$ ssh-keygen -t rsa -C "youremail@example.com"
   b. GitHub ���� setting\SSH\Add new SSH ,title �����KEY�н����渴�Ƶ�����������

   c. ͬ������
	$ git remote add origin git@github.com:Rains-2018/AndroidStudio.git
	$ git push -u origin master

9. ���ش����޸�ͬ��������
   $ git add readme.txt	
   $ git commit -m "New File to Studio Git"
   $ git push -u origin master	

10. ��GitHub��ȡ����
    $ git clone git@github.com:Rains-2018/AndroidStudio.git	

11. ��GitHub�ϸ������´���
    $ git pull