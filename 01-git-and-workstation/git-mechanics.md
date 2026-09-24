## git creation 
befor git, a team of tow, one front-end one back-end devolopers would waist a lot fo time one waiting for the other to finish it work to be able to devolop his part on the newest version of the code.

git presented it solution with main branch and branches . evryone take the laytest virsion of the code work on it and just merges it if it is good after word with the main.

## github
* github is a proprietary cloud platform owned by microsoft.it uses git engine with additional front page and extra tools to make smoother and rasier workflow thoughout the team.

## git terms
*  repository (repo) the database, the folder we are going to work on.
*  local repo the local database in you pc.
*  remote repo the shared database with the whole team ,send on the leatest versions and branches like github.

## gti commands 
* `git init` prepares the folder so git can start detecting it
* `git status` it detect and tell you wehere any chnages were made inside your local repo
* `git add` it adds the files to the detector 
* `git commit -m "message"` saves a permanent snapshot of staged files into your local repository history
* `git restore --staged` it removes the files from the detecor
* `git remote add origin <link>` Connects your local repo to the remote github cloud repo so you can exchange data
* `git remote -v` present the url that you foder is linked to
* `git push origin main` uploads you local checkpoint to the remote repo
* `git pull origin main` downloads the remote repo in you local repo so you don't work on an old version code
* `git branch` shows the list of branches on your machine
* `git branch name` creates a new branch
* `git checkout name` changes you  from a branch to another
* `git merge name` merges your branch with the main one
* `git branch -m name1` changes the name of the branch
* `git branch -d name` deletes safely a branch if there are no unmerged commits
* `git branch -D name` deletes a branch even if there are unmerged commits<>