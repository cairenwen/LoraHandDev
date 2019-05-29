git is a version control system
git is free software
git is a new tool for me 
工作区 暂存区 版本库

1.工作区修改了内容 ：checkout 
					A.add过了，会退到暂存区
					B.还没有add，会退到版本库最新版本
2.工作区未修改内容，已经add了，还未commit：git reset HEAD <file> 撤销暂存区，重新回到工作区修改内容状态

3.已经commit：git reset --hard HEAD^
                    
					
