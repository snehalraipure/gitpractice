git init ----------used for once only when you start working with git on new folder.
git status --------this is used to check the status of the folder that all the files are part of git or not.


If you are going to add any new file in the folder then check with git status and it will
show you untracked file. To make this part of git you need to perform git add git commit.


git add .
git add *

git commit -m "initial commit"

use different commands like add and commit seperately when adding any file for the first
time in git.  

git commit -a -m "message"-----------------this will only used for those files.  



### use below commands for only oce when pushing data for the first time

git branch -M main
 git remote add origin https://github.com/snehalraipure/gitpractice.git
git push -u origin main
