git clone  repository_url - it is a command used to import or copy the repository from Git hub server (VCS) to the local system
 
2) git init -git init is one way to start a new project with Git. To initialize a repository, Git creates a hidden directory called .git. 
That directory stores all of the objects and refs that Git uses and creates as a part of your project's history. 
This hidden .git directory is what separates a regular directory from a Git repository.

3) git branch - this command is used in git bash to create a new branch in the repository

4) git checkout -b branch_name  - this command is used to create a branch and swith to the newly created branch

5) git add filename - this command is used to track and add the created file to the staging area

6) git add *  - this command is used to track and add the created file to the staging area

7) git add .  -this command is used to track and add the multiple created files to the staging area

8) git status - this command is used to check the status of tracked file, it will check if it is new file or modified file 
		after using git add command

9) git diff - this command is used to know the changes made in the file

10) git commit -m "message" The git commit command will save all staged changes,
 along with a brief description from the user, in a “commit” to the local repository.

11) git push origin branch_name      git push origin will push changes from all local branches to the remote branch

12) git pull origin branch_name     git pull origin will import or pull changes from all remote branches to the local branch

13) git fetch --all         this command pulls all the remote branches and commits

14) git merge branch_name   Git merge is a command that allows you to merge branches from Git. Merging is a common practice for developers. Whether branches
 are created for testing, bug fixes, or other reasons, merging commits changes to another branch. It takes the contents of a source branch and integrates it 
with a target branch.

15) git config --list -  The git config list command will show all Git config properties throughout all of the variously scoped Git files.

16) git config --global user.email "youremail"  It is important to configure your Git username and email address as every Git commit will use this information
 to identify you as the author. You'll need to do this only once as you are using the --global option. It tells Git to always use this information for anything 
you do on that system.

17) git remote -v - If you have more than one remote, the command lists them all. For example, a repository with
multiple remotes for working with several collaborators
