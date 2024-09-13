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

### after using above commands for repo/folder u need to use given command to upload data every time
git push

###
git remote -v
git remote ----to check vaiable
git log
note:-"after git log performed...to come outside it we have to perform q command"
git remote rm origin2 -----to delete any variable
git rm --cached < file name > -----it will be in our windows only from small memory it will be removed.
.gitignore file ---- add name waste.html there then git will ignore it in its commands.
git rm < file name > ---to permanently delete the file
creation of gitignore
git mv < old file name > < new file name > ----to rename 
git clone---keep in laptop
fork---- repository copy will keep online (github)  
git diff---it tells the difference which we made in file
git diff file name