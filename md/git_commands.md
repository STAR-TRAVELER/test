1. git config --global user.name "Your Name"
2. git config --global user.emil "email@example.com"
3. mkdir learngit
4. cd learngit
5. la -a //查看当前目录内容
5. pwd //查看当前目录
6. git init //初始化仓
7. git add read.txt //向缓冲区添加文件
8. git commit -m "worte a read.txt" //向仓添加文件  
9. git status //查看状态  
10. git diff  read.txt //查看修改后与修改前的不同  
11. git log//查看历史记录  
12. git log --pretty=oneline//每条记录只占一行  
13. cd ..\  
14.  git reset --hard HEAD^//回退上个版本，上上一个版本就是HEAD^^，当然往上100个版本写100个^比较容易数不过来，所以写成HEAD~100
15. cat read.txt //查看文件内容
16. git reflog //git reflog用来记录你的每一次命令
17. git checkout -- read.txt //意思就是，把readme.txt文件在工作区的修改全部撤销。  
 一种是readme.txt自修改后还没有被放到暂存区，现在，撤销修改就回到和版本库一模一样的状态；  
一种是readme.txt已经添加到暂存区后，又作了修改，现在，撤销修改就回到添加到暂存区后的状态。  
19. red
20. 20. git reset HEAD readme.txt //可以把暂存区的修改撤销掉（unstage），重新放回工作区.
21. git rm test.txt //删除文件
22. 


[more commands](https://www.cnblogs.com/cspku/articles/Git_cmds.html)