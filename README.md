# Hendershot-Shaw

//--Common GitHub commands--//

-Git clone: git clone <https://name-of-the-repository-link>
Git clone is a command for downloading code from the github. In other words, it makes an identical copy of the latest version and saves it to your computer.
There are a couple of ways to download the source code, but mostly I prefer the clone with https way: 


-Git branch: git branch <branch-name>
Branches are highly important in the git world. By using branches, several developers are able to work in parallel on the same project simultaneously. We can use the git branch command for creating, listing and deleting branches.


-Git checkout: git checkout <name-of-your-branch>
This is also one of the most used Git commands. To work in a branch, first you need to switch to it. We use git checkout mostly for switching from one branch to another. We can also use it for checking out files and commits. There is also a shortcut command that allows you to create and switch to a branch at the same time: git checkout -b <name-of-your-branch>


-Git status: git status
The Git status command gives us all the necessary information about the current branch. 

-Git add: git add .
When we create, modify or delete a file, these changes will happen in our local and won't be included in the next commit (unless we change the configurations).
We need to use the git add command to include the changes of a file(s) into our next commit. 

-Git commit: git commit -m "commit message"
This is maybe the most-used command of Git. Once we reach a certain point in development, we want to save our changes (maybe after a specific task or issue).
Git commit is like setting a checkpoint in the development process which you can go back to later if needed.
We also need to write a short message to explain what we have developed or changed in the source code.

Git push: git push
After committing your changes, the next thing you want to do is send your changes to the remote server. Git push uploads your commits to the remote repository.

Git pull: git pull
The git pull command is used to get updates from the remote repo. This command is a combination of git fetch and git merge which means that, when we use git pull, it gets the updates from remote repository (git fetch) and immediately applies the latest changes in your local (git merge).



