# Git Tutorials

Hello, I'm learnig Git & Github with the help of stacklearner.

Like my [Facebook](https://facebook.com/ohidbd) Profile.

## Initial Command (Create new repository on the command line)
* echo "# a" >> README.md
* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin https://github.com/fsd-ohidur/***.git
* git push -u origin main

## Push an existing repository from the command line
* git remote add origin https://github.com/fsd-ohidur/a.git
* git branch -M main
* git push -u origin main
  
### Initiaze git for first time
git init

### Check git status
git status

### add untracked files to tracked
* git add .
* git add file_name

### Remove tracked files
a. File by file
* git rm --cached filename

b. Hard reset
* git reset --hard

### Commit Staged File(s)
git commit -m "Commit message"

### Move to any stage
a. check log
* git log

b. Copy any ID
c. Checkout ID
* git checkout ID

### Move to main
* git checkout main

### Work with branch
a. Show branches as list (active branch shown as *)
* git branch

b. Create new branch (Suppose we are now in main branch)
* git branch branch_name
-- now we have a copy branch of main branch

c. Activate or Move to new branch
* git checkout branch_name

d. Crate a new branch and move/checkout to that branch
* git checkout -b branch_name

### Check difference main with new branch and merge that
a. Move to main branch
* git checkout main

b. check Differences
* git diff

c. Check difference main with branch
* git diff main..branch_name

d. Merge branch with main
* git merge branch_name
* git merge branche_name1 branch_name2

### Work with Stash (Need when temporarily checkout from one branch to another)
a. Check Local changes to save
* git stash

b. Save Stash
* git stash save "message"

c. Check stash list
* git stash list

d. Retrieve saved last stash (retrive like data structure stack) 
* git stash pop 


### Add information to config
* git config --global user.name 'username'
* git config --global user.email 'email of user'

### Push to Remote server
a. Push Main
* git push -u origin main

b. push branch
* git push -u origin branch_name

c. push main or multiple branch
* git push -u origin main branch_name1 branch_name2


