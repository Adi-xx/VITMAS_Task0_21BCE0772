# VITMAS_Task0_21BCE0772

## GIT COMMANDS

### 1) GIT CONFIG
This command sets the author name and email address to be used with your commits

Syntax -  

          git config -global user.name "name"
          git config -gloabal user.email "email"
         
### 2) GIT INIT
This command is used to create a new repository

Syntax - 

          git init [name]
          
### 3) GIT CLONE
This commant is used to obtain a repository from an existing URL

Syntax -  

          git clone [url]
                       
### 4) GIT ADD/ADD *
This command adds a file to the staging area/Adds one or more files to staging area

Syntax - 
          
          git add [file]
          
### 5) GIT COMMIT
This command records or snapshots the file permenently in the version history.

Syntax - 
          
          git commit -m "(type in the commit msg)"
          
### 6) GIT COMMIT-A
This command commits any file you have added with the git add command and also commits any files you have changed since then.

### 7) GIT DIFF
Shows the file differences which are not yet staged

Syntax -
             
           git diff
           
### 8) GIT STATUS
Lists all files that have to be committed.

Syntax - 

           git status

### 9) GIT RM
This command deletes the files from your working directory and stages the deletion.

Syntax -

           git rm[file]

### 10) GIT Log
This command is used to list the version history for the current branch.

Syntax -

           git log
           
### 11) GIT SHOW
This command shows the metadata and content changes of the specified commit.

Syntax - 

           git show [commit]
           
### 12) GIT TAG
This command is used to give tags to the specfied commit.

Syntax -  
          
          git tag [commitID]
          
### 13) GIT BRANCH
Lists all local branches in current repository.

Syntax -  
          
          git branch
          
This command creates new branch

Syntax -  
          
          git branch [branchname]
          
This command deletes the feature branch

Syntax -  
          
          git branch -d[branch name]
           
   
### 14) GIT CHECKOUT
Used to switch from one branch to another. It can also create a new branch and then switch to it

Syntax - 

          git checkout [branchname]
          git checkout -b[branch name]
          
### 15) GIT MERGE
Merges specified branch history into the current branch.

Syntax - 
           
           git merge [branch name]
           
### 16) GIT REMOTE
Used to connect local repository to the remote server.

Syntax -  
           
           git remote add[var name][Remote server link]
           
### 17) GIT PUSH
Sends committed changes of master branch/branch commits/pushes all branches to your remote repository.

Syntax -  
          
          git push [var name] master
          git push [var name] branch
          git push -all[var name]
          
### 18) GIT PULL
Fetches and merges changes on the remote server to your working directory.

Syntax -  
          
          git pull [Respo link]
          
### 19) GIT STASH

Syntax -  
          
          git stash save - Temporarile stores all modified tracked files
          git stash pop - Restores the most recently stashed files.
          git stash list - Lists all stashed changesets
          git stash drop - Discards the most recently stashed changeset.
