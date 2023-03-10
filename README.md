# Summary

## Week 1

-   git --version
-   git init
-   git status
-   git config --global user.name (credential)
-   git config --global user.email (credential)
-   git config --list --show-origin
-   create PAT (private access token)
-   .gitignore file
-   git clone

### Addition

-   https://<u><b>PAT</b></u>@github.com/63070118-Pithawat/midterm.git -> create remote using PAT

## Week 2

-   git add <u>path</u> -> move the target file to <b>staging area</b>
-   git commit -m "<u>checkpoint</u>" -> move the file from staging area to <u>repo</u>
-   git pull <u>remote</u> <u>branch</u>
-   git remote -v -> check remote with verbose detail
-   git remote add <u>name</u> <u>remote repo</u> -> create remote/pipeline for pushing local repo onto cloud repo
-   git rename <u>old</u> <u>new</u> -> rename remote in local
-   git remote remove <u>name</u> -> delete remote from local
-   git push -u origin <u>branch</u> -> push local repo onto cloud with new branch
-   git push origin <u>branch</u> -> push local repo onto cloud
-   git push -f origin <u>branch</u> -> push local repo onto cloud with force option will replace the same file
-   git push -F origin <u>branch</u> -> push local repo onto cloud with Force option will destroy the pass and create new one
-   git branch -M <u>name</u> -> rename a branch doesn't care exists or not
-   git branch -r -> check exists branch
-   git checkout <u>branch</u> -> switch from one branch to another branch
-   git log -> tracking the commit timeline
-   git log --oneline -> seeing history of commit with one line
-   git fetch <u>remote</u> && <u>branch</u> -> pull the cloud repo into local repo
-   git pull <u>remote</u> && <u>branch</u> -> pull the cloud repo into working station || git fetch + git merge

### Addition

-   default branch on github -> main

## Week 3

-   git branch ->
-   git switch -> can be change the HEAD to latest commit of the branch
-   git checkout -> can be change the HEAD to commit ID
-   git diff -> compare current branch with target
-   git merge -> merge current branch with target
-   git branch -> check all branch
-   git branch -m <u>new_name</u> -> rename current branch
-   git branch -d <u>branch</u> -> delete only merged branch
-   git branch -D <u>branch</u> -> force to delete branch

### Addition

-   HEAD -> has been always pointing at the latest commit
-   merge types -> 1. fast forward | 2. conflict

## Week 4

-   git restore -> working like cmd+z (back to latest version)
-   git restore --source HEAD~N . -> restore everything to HEAD_ID
-   git restore --staged . -> restore everything from staging area
-   git reset <u>commit_id</u> -> back to the commit_id without change
-   git reset <u>commit_id</u> --hard -> back to the commit_id destroy everything then rollback to commit_id

## Addition

-   git push --all -u <u>remote</u> ->create new branch on repo and push
