git is a version control system
git is free software
git is a new tool for me 
工作区 暂存区 版本库

1.工作区修改了内容 ：checkout 
					A.add过了，会退到暂存区
					B.还没有add，会退到版本库最新版本
2.工作区未修改内容，已经add了，还未commit：git reset HEAD <file> 撤销暂存区，重新回到工作区修改内容状态

3.已经commit：git reset --hard HEAD^

4.删除也是一种修改
	1.如果你用的rm删除文件，那就相当于只删除了工作区的文件，如果想要恢复，直接用git checkout -- <file>就可以 
	2.如果你用的是git rm删除文件，那就相当于不仅删除了文件，而且还添加到了暂存区，
	需要先git reset HEAD <file>，然后再git checkout -- <file> 
	3.如果你想彻底把版本库的删除掉，先git rm，再git commit 就ok了
	
试试看
                    
					
