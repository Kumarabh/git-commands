# git-commands

#### Unstage a file
$ git restore package-lock.json --cached
#### Delete a branch locally
$ git branch branchName --delete
#### Delete a branch remotely:
$ git push origin branchName --delete
#### Git pull for unrelated history
$ git pull origin branchName --allow-unrelated-histories

-------------------------------------------------------------------------------------------

#### Show diff of a file w.r.t stage
$ git diff file2.txt

#### Log last 5 commits
$ git log -n 5

#### Log last commit
$ git log -1

#### Show changes of last commit
$ git show b7cac31a7680874f79177fa021f8246d9b6093fb

#### BRING COMMITED CHANGES TO STAGING AREA + DELETES STAGING AREA + WORKING DIRECTORY - Undo the last commit and remove all changes in working directory - 

$ git reset --hard <Commit ID>
$ git reset --hard HEAD^1 OR
$ git reset --hard HEAD^ OR



#### BRING THE COMMITED CHANGES TO STAGING AREA - KEEP STAGING AREA + WORKING DIRECTORY - Undo the last commit and bring the commited changes in to staged and leave working directory changes as it is - 
$ git reset --soft HEAD^1
