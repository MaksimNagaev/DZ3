# Basic instructions for Git 

## Start steps:

1. Install programm from Git site - **(https://git-scm.com/)**

2. Check how it works with command: *git --version*  
(**if all going right - you will see actual version of your git**)

3. Creating a repository - choose folder of your project by: **File - Open Folder**

4. Initializing your folder as a repository with command: *git init*

5. Create your own profile in Git system with next commands:
    * *git config --global user.name "Your name"*
    * *git config --global user.email "Your email"*

Well done! Your first Git repository is create!

## Basic commands:

- *git help* - help for all commands;

- *git add .* - add all files in this repository to future commit;

- *git add --all* - same comand as previous;

- *git add "File name"* - add to future commit only specific file;

- *git commit -m "Our comment"* - record changes to the repository with your comment;

- *git commit -**a**m "Our comment"* - allows you to combine "git add" with previous command - it allows you to avoid unnecessary actions;

- *git status* - shows to you versions information on current files;

- *git log* - shows to you information about save checkpoints;

- *git log __--graph__* - shows to you current branch ways;

- *git reflog* - a similar command in a more compact form and including checkpoint load log;

- *git checkout "savepoint code"* - loading a specific savepoint - by full or short code (4 digits);

- *git checkout master* - loading your master savepoint;

- *git diff* - show changes between current work and last commit;

- *git branch* - information menu about all current branches, as well as the basis of commands for working with them like:  
    1. *git branch __new_branch_name__* - creating a new branch with specified name;
    2. *git branch __-d__ new_branch_name* - removal a branch with specified name;

- *git merge new_branch_name* - including all changes from specified branch to current - This can lead to two kinds of developments:  
    1. 1. Standard inclusion of all changes in the current branch from the one you selected in the command;
    2. Creation of a conflict that requires your direct participation in decision making;

## Tips and Hints

- *.gitignore* - a way to exclude items you don't care about from the Git tracking system. Details in the picture:

![.gitignore work example](Images\Gitignore_example.png)


### This guide may be updated in the future.

