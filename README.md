1. `git init`->powers your folder to manage by git and initialises a new repository .
 It also creates a .git folder that has all the revelant logic to manage versions of your project

                 Inside Git there are three areas divided where our code chages occurs    

2.  `Working Area`->There can be a bunch of files that are not currently bunch by git .
 It means changes done or can be done in those files that are not managed by git.A file that is in working 
 area is considered to be not in the staging area. When we do `git status` and we see abunch if `umtracked files`
 then these are actually called in working area;


3.  `Staging Area`->What are files are going to be part of the next version we will create .
 This staging area is the place where git knows that chnages will be done in the last version to the next version.


4.  `Repository Area`->This area actually contains all the details of all your previous registered version.
 And this file in this area ,git already manages them  and knows their history.


5. `git add <file>`->moves file from working area to staging area

6. `git rm --cached <file>`->moves file back from staging area to working area

7. `commit`-> commit is a particular version of the project.It captures a snapshot of the project's staged changes
 and creates a version of out of it.

8. `git commit`->register staging chamges to commit
9. `git log`->list down all the commits of the repository.if you want to exit out of git log then press `q`
10. `git restore <file>`->It removes all the files chages from the staging area to be commited .This can be useful.
If we did some dirty part of the code and now no more of it then instead of deleting every change line by line ,we 
can restore it or you can say restore last clean version of the file  
11. `git comit -m "<your commit message>"` -> If we want to avoid opening a text editor like vim/nano to add commit message we can use the following commands

12. VS code shows green bar which means all these in working area.
  
13. `git remote`->list down all the connection name
14. Remote Connection->It helps you to link two git repositories for uoploading and downloading the changes 
15. `git remote add <name of remote> <link of remote>`->this command helps to add the new link to the remote repo  and give a name to it
16. `git remote rm <name of remote>`:this commands delete the remote connection

17. `git add <file1> <file2> <file3>`: This command will add multiple files togetheer in staging area 
18. `git add .` : this command adds all files to working area to staging area.
19. `git pull <remote name> <branch name>`:download the latest changes form the branch of the mentioned remote in your local repo .

   ### Recommended practice to do so

       - make changes 
       - git add <files>
       - git commit 
       - git pull
       - git push 