

#Git and Git Hub
================
git - version control system (VCS) 
github - remote repository hosting service 



#1.clone from remote repo:
=========================
git clone git@github.com:SandeepNookala/Git.git

#2:create local branch:
=======================
git checkout -b git_update


#Move files from working directory to stagging area


#3.adding a file:
=================
git add file.txt 


#4.adding all files:
====================
git add .


#5.rename the file name:
========================
git add -u 


#6.check status:
================
git status


#7.commit changes to local repository:
=====================================
git commit -m 'first commit'


#8.link remote repository with local repository:
===============================================
git remote add origin https://github.com/SandeepNookala/Git.git


#9.push code from local to remote for creating pull request:
===========================================================
git push -u origin git_update


********************************************************************

#1.List all git branches:
=========================
git branch -a


#2.Delete git branch:
=====================
git branch -d gitflow 


#3.switch to branch: 
====================
used to switch branches, whenever the work is to be started on a different branch.

git checkout gitflow2


#4.switch to master: 
====================
used to switch to master

git checkout master


#5.git merge:
=============
The git merge command is used to integrate the branches together.The command combines the changes from one branch to another branch. 

git merge <branch_name>


#6.git pull:
============
The git pull command is used to fetch and merge changes from the remote repository to the local repository.

git pull <branch_name> <remote URL>


#7.check linked repo:
======================
git remote -v


#8.git config:
==============
This specifies what email id and username will be used from a local repository.

git config


#9.authorization git dash and git hub:
======================================
git config --global user.email “nookala382@gmail.com”
git config --global user.name "Sandeep"


git config --global user.email “satishnookala561@gmail.com”
git config --global user.name "SatishNookala"


#10.git log:
============
It is used to view the entire commit history

git log


#11.git diff:
=============
Displays the difference between files in two commits or between a commit and your current repository

git diff

#12.merge conflict:
==================
manual intervention needed .should take decision based on situation
1. Accept the incoming changes
or
2. push my changes
or
3.keep both changes


#13.Synchronizing a local Git repository with a remote one:
*******************************************************
git fetch --prune
