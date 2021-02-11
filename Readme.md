Version Control:
================
+ Version cotrol is a system thar tracks the changes to a file or files or project over a time
+ Distributed Version Control System(DVCS)
	+ Git,Mercurial
+ Central(Remote) VCS
	+ Github,Apache subversion

Uses of Git&Github:
===================

+ To complete the Global certifications like Google,Udacity,Courseera
+ To track the files in a project

Git Commands:
==============
+ cd foldername--> change directory
+ ls --> List of files
+ ls -a --> To see hidden files
+ touch filename -- > to create a file
+ nano filename --> It will create file and open nano editor
+ ctrl+x -- > to quit the file
+ click on `Enter` filename to write :reg.html |

+ Editing file using vim editor
+ vim filename -- > filename open with vim editor
+ `ctrl+c`
+ At the bottom of the file type `:w` to save the code
+ `:q`  to exit the file

Git Structure:
==============

+ Untracked area
	+ `git status` -- > To know the status of files
	+ `git init` -- > To initialize git repository
	+ `ls -a`  --> to see hidden git repository
	+ `git add filename` --> To add file to git
	+ `git add . or git add --all` --> To add all files to git repository
	+ `git status`
	+ `git rm --cached filename`-->Remove file from stagging area to untracked area
	+ `git status`
	+ `rm filename` --> to remove file
	+ git commit -m "basic data"
	+ Config user name and email
	+ if git contains previous user name and email
	   check username with `git config --global user.name` , Similarly check user email with `git config --global user.email`
	+ If you are not the user try to delete previous user data 
	    + Goto `win+s` Credential manager-> windows credentials --> remove git credentials
		+ To remove username `git config --global --unset user.name "KalyanPaladugu"`



+ Stagging area
+ Commit area






















