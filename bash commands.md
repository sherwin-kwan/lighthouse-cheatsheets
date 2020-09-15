<!--- Some simple commands to help you with using the shell. These instructions are for Bash, the standard command line interface in most Linux distributions.
You are using Bash whenever you are on your Lighthouse Labs VM connected through Vagrant. If you have a Linux system on your own computer,
you are most likely also using Bash whenever you open a terminal emulator like GNOME Terminal, Konsole, or Xterm. 
Mac OS users: Your shell is called Zsh, which is a slight variant of Bash, all the basic commands here should still work. -->

Whenever you use the command line, you are always "in" a particular folder. So first, you need to find your way around:

## Finding Your Way Around

* **pwd**: Outputs the current folder you are in
* **ls**: Tells you what files and folders are in your current folder
  * *ls -a* will show hidden files and folders too
  * *ls -l* will show you permissions for each file and folder too (like, who can open or edit files in each folder)
* **cd (address)**: Change directory - change to a different folder
  * *cd 
  
## Relative Addresses

* **.**: The folder you're in right now
* **..**: The folder immediately above this one

## File and Folder Management

* **touch (filename)**: create a file
* **rm (filename)**: delete a file (WARNING: this is forever! it doesn't even go to trash, it's gone!)
* **mkdir (foldername)**: create a folder
* **rmdir (foldername)**: permanently delete an *empty* folder 
* **rm -r (foldername)**: permanently delete a folder and all the files and folders inside it

## Git

* git init: enable Git in a directory (this creates a hidden /.git folder)
* git remote: use for initial setup of your connection with a remote repo like Github
* git add: move from your working directory to staging area
* git commit: move from staging area to local repo
* git push: move from local repo to remote repo
* git pull: move from remote repo to local repo

