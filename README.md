# Git-Tutorial
All basic comands to use git and git hub

## To set git on your machine

inside a folder, right click the mouse and select “Git Bash Here”

`git init` ( It start the git in the folder )

`git status` ( It shows track, untrack files, comits)

`git add` “FileExemple.txt” ( It start tracking an specific file)

`git add .` (track all files in the folder)

`git commit -m “describe your changes in the file”` (commit only save changes on your machine)

`git remote add origin /repository url/` (It connect your local repo to a github repo)

`git push` (It send the changes to your github repository)

but, you need to specify the branch (temporal line)

`git push —set-upstream origin /branchName/` (this will push to the specified branch)

`git reflog` (It shows all the commits done to that file, It shows all versions of your file)

`git reset —hard /yellow id/` (Here is were you can time travel, It change the file to a specific commit)

## Branches

`git branch` (It shows all branchs, the green one is the branch you currently working on)

`git branch /branchName/` (It creates a new branch)

`git checkout /branchName/` (changes wich branch will recive the commits)

## Merge

`git checkout /branchName/` (first, you need to set as main the branch you want to pull the modifications)

`git pull` (before go merging things, you need to update all your branches, with the remote data on your git hub, just if you are working with someone else)

`git merge /branchName/` (this make the branch you specify here, overlap the main you set before)