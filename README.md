# test-repo
This repo is used for getting hands on experience for using git and github.
<br>
README.md file is used for giving long discription about our code.<br>
1)First of all whenever you will get an task we have to clone the main repo in our local system and work on it.<br>
For cloning use this command " git clone 'some link' ".<br>
2)Use "ls" command to see files present in repo.<br>
3)Use "ls -a" command to see files present in repo. If in this command you see " .git " then this file has git already initialized and it is tracking it.<br>
4)If not then we have to first initialize git for that we use " git init".<br>
5)We have a command " git status " which shows us state of the code like staged,unmodified,modified,untracked.<br>
6)Now to track our changes in the file we have to add the changes in git staging area. Use command " git add 'file name' " or " git add . "<br>
7)Once your work is done add the file and then commit it (it is record of changes), if you are working on your project.<br>
Use command when working on command line " git commit -m'some message' ".On github you have a button to commit changes. <br>
If not then raise a pr (pull request) which will be scrutinized by head then if everthing is proper they will merge it with the main branch.<br>
8)Now imagine we have made changes in our file and commit it, now if you use git status then you will see you are ahead of ' main ' by 1 commit. If you check your github it will not show any changes if you want to see the changes made on your local system globally on github you have to use "git push command".<br>
use command "git push origin main". now refresh github you will see the changes.<br>
9)Pull command is used to download content from remote repo to local repo to match the content.
use command "git pull origin main".
