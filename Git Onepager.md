# Onepager

## Git branching strategy
Main
Long lived branches (development, staging) They persist in the code. 
Short lived branches (feature) they are deleted after you are done with them

## git checkout branch-name
Checout to selected branch

## git add filepath/filename
To add a file to a commit

## git add -p filepath/filename
p stands for pach. Allows you to pick single changes to add to the commit

## git commit
will commit staged changes. After giving title & description use :wq to exit the editor and proceed

## git push repo-name branch-name
Pull requests are used to contributing to other repositories or asking for comments.
For example you might have a fork (a copy of the code where you make changes) and you want to suggest thos changes to be included via a pull request.
Pull requests are based on branches that you later request to be included
Git push will push the commits from branch name to repo name, creating a pull request

## git pull
Incorporates changes from the named commits
Assume the following history exists and the current branch is "master":

	        A---B---C topic
	       /
    D---E---F---G master
    
Then "git merge topic" will replay the changes made on the topic branch since it diverged from master
	        A---B---C topic
	       /         \
    D---E---F---G---H master


## git merge


## git branch branch-name
Used to create new branches
