`git init`->powers your folder to manage by git and initialises a new repository .
 It also creates a .git folder that has all the revelant logic to manage versions of your project

                 Inside Git there are three areas divided where our code chages occurs    

 `Working Area`->There can be a bunch of files that are not currently bunch by git .
 It means changes done or can be done in those files that are not managed by git.A file that is in working 
 area is considered to be not in the staging area. When we do `git status` and we see abunch if `umtracked files`
 then these are actually called in working area;


 `Staging Area`->What are files are going to be part of the next version we will create .
 This staging area is the place where git knows that chnages will be done in the last version to the next version.


 `Repository Area`->This area actually contains all the details of all your previous registered version.
 And this file in this area ,git already manages them  and knows their history.


 `git add <file>`->moves file from working area to staging area

 `git rm --cached <file>`->moves file back from staging area to working area

 `commit`-> commit is a particular version of the project.It captures a snapshot of the project's staged changes
 and creates a version of out of it.
