# Git-and-Github-
version control with git and github notes.
->  learn basic git commands : init, add, commit, push, pull.
->  use github for project hosting.

STEPS:-

1. download git from - git-scm.com/downloads
2. open git-bash.

    TRY BASIC COMMANDS:-

     * git --version : gives us git bash version.
     * ls: gives list of files/folders/directory.
     * clear or ctrl+l : clears the screen.
     * pwd: shows the current working directory .


    CONFIGURE GIT:-

     * git config --global user.name "my name"
     * git config --global user.email "someone@gmail.com"
     * git config --list : shows your created user name and email.

3. create a folder gitdemo .
4. open it with vs.code  .  
5. - In vscode open terminal and you can check version of git there also using  : git --version
   - To clear screen you can use cls or clear.

CLONE AND STATUS:-

* clone: cloning or copy a repository on our local machine/laptop/pc.
      -> git clone <-some link or your github repo/project  link->  (use this command in vscode terminal to get your github
          repo files/folders in your gitdemo of vscode )
      -> use cd <folder name > : to go inside your folder (in terminal)
      -> ls : to list files in that folder.
      -> ls -a : shows hidden files also.
  
* status: displays the state of code.
<<<<<<< HEAD
      -> git status (in vscode terminal)

  4 TYPES OF STATUS :-

1. untracked : new files that git dosent  yet tracked 
2. modified : changed
3. staged : file is ready to be commited 
4. unmodified : unchanged



