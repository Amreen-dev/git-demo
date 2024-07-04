##Clone a repository into local
git clone <SSH_clone_url>

## Command to create a new git branch, here the branch name is feature-001
git checkout -b feature-001

#list the branches and check what branch you are on
git branch


## swith to a branch other than what you are on currently
git checkout main


##Make changes to the code files


## Step 2: Check the status, if changed files are unstaged
git status

## Step 3: Now add files to stage for commit
git add . 

## Step 4: check the status, if all changed files are ready to be committed
git status 

## Step 5: Write a commit message for the changes done
git commit -m "Commit message , explaining what changes have been added"

## Step 6: Push the files from local to the git repository into the intended branch ; Here feature-001 is the branch name
git push origin feature-001



### git stash
## git revert
## git reset
## git rebase
## git pull
## git merge