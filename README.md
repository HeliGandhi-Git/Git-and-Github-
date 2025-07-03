# Git-and-Github-
#version control with git and github notes.
->  learn basic git commands : init, add, commit, push, pull.
->  use github for project hosting.

#STEPS:-

1. download git from - git-scm.com/downloads
2. open git-bash.

#TRY BASIC COMMANDS:-

   -> git --version : gives us git bash version.
   -> ls: gives list of files/folders/directory.
   -> clear or ctrl+l : clears the screen.
   -> pwd: shows the current working directory .


#CONFIGURE GIT:-

  -> git config --global user.name "my name"
  -> git config --global user.email "someone@gmail.com"
  -> git config --list : shows your created user name and email.

3. create a folder gitdemo .
4. open it with vs.code  .  
5. - In vscode open terminal and you can check version of git there also using  : git --version
   - To clear screen you can use cls or clear.

#CLONE AND STATUS:-

  * clone: cloning or copy a repository on our local machine/laptop/pc.
      -> git clone <-some link or your github repo/project  link->  (use this command in vscode terminal to get your github
          repo files/folders in your gitdemo of vscode )
      -> use cd <folder name > : to go inside your folder (in terminal)
      -> ls : to list files in that folder.
      -> ls -a : shows hidden files also.
  
  * status: displays the state of code.
  
      -> git status (in vscode terminal)

#4 TYPES OF STATUS :-

 1. untracked : new files that git dosent  yet tracked 
 2. modified : changed
 3. staged : file is ready to be commited 
 4. unmodified : unchanged

#ADD AND COMMIT :-

 * add : adds new or changed file in your working directory to the git sraging area.
  -> git add <-file name-> OR
  -> git add . (for saving changes in all the files)

 * commit : it is the record of change.
  -> git commit -m"some meaningful message"


#PUSH COMMAND :-

   * push : upload local/laptop/pc repository content to remote repo in GitHub.
       -> git push origin main    (default)

#INIT COMMAND :-

   * init : used to create a new git repo.
        -> git init   (initialize)
        -> git remote add origin <-link->  (remote = repo ,to add new repo)
        -> git remote -v    (to verify remote ) 
        -> git branch    ( to check branch)
        -> git branch -M main   (to rename branch )
        -> git push origin main
        -> git push -u  origin main   (then we only have to write git push every time.)
        -> cd ..    (comes out from current folder/directory)
        
6. mkdir LocalRepo (folder name ) :-
    (you can make new folder /directory using this command )

    > we created the new folder named LocalRepo in vscode


#WORKFLOW :-

  -> Local Git :         > GitHub repo initialize 
                                    |
                                > Clone
                                    |
                                > Changes
                                    |
                                >  add
                                    |
                                >  Commit
                                    |
                                >   Push  

#GIT : BRANCHES :-   

                                (feature)
                        c3   c4    c5
                --------O----O-----O---| 
    O----O-----|--------O----O-----O---|-------O (merge)                      
    c1   c2             c6   c7    c8         c9
                                 (master)  
 

#BRANCH COMMANDS :-

   -> git branch      (to check branch)
   -> git branch -M main    (rename branch)
   -> git checkout  <-branch name->     (to navigate)
   -> git checkout  -b <-new branch name->    (to create new branch)
   -> git  branch -d <-branch name->    (to delete branch)


#MERGING CODE :-

  * Way 1 :  -> git diff <-branch name->    (to compare commits ,branches, files, & more)
             -> git merge <-branch name->   (to merge 2 branches)

    note: press q to exit diff viewer.

  * Way 2 : create a PR.

#PR (PULL REQUEST) :-
 -> It lets you tell others about changes you have pushed to a branch in a repo or GitHub.

#PULL COMMAND :-

  -> git pull origin main
  -> to fetch and download content from a remote repo and immediately update the local repo to 
     match that content.

#RESOLVING MERGE CONFLICTS :-

  -> An event that takes place when git is unable to automatically resolve differences in code between two commits.


#UNDOING CHANGES :-

  -> case 1: stages changes 
         - git reset <-file name->
         - git reset
  -> case 2: commited changes (for one commit)
         - git reset HEAD~1     (head tilt 1)
  -> case 3: commited changes (for many commits)
         - git reset <-commit hash->
         - git reset --hard <-commit hash->
         - git log (to see hash of commits)

#FORK :-

   -> A fork is a new repo that shares code and visibility settings with the original "upstream" repository.
   -> Fork is a rough copy.

   
