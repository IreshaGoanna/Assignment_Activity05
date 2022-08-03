# Activity 5
***Use and Management of VCS in this project***

## Difficulties or challenges during development:
No specific difficulty or challenge so far.

## How this VCS has complied with the organisational requirements
In order to comply with organisational requirements in, Git has been chosen to be used as a distributed version control system that most developers are familiar with, and has good online supporting ecosystems.

## How you verified the VCS was performing as expected:
Once the VCS was deployed, it is possible to check if everything is set properly by using ```git config --list --show-origin``` and review settings.

### Branches
As a part of organisational requirements, All development in the version control system must take place on feature branches, so the main branch is exclusively initialisation and then merges. </br>
Two branches are created : **"documentation"** for managing the documentation tasks and **"coding"** for implementation of the program. Below are the commands that can be used in **main branch**: <br/>
```git branch documentation``` <br/>
```git branch coding``` <br/>


### Stages
A file in a repository can be either tracked or untracked by Git; tracked files are those that Git will keep track of over commits. Untracked files are those that Git does not track. 
In order to avoid unnecessary trackings, **.gitignore** is used to store which file are not to be tracked in each branch.</br>
In this project below files and folder are added to **.gitignore** in coding branch:</br>
Documents/* </br>
node_modules/* </br>
package-lock.json </br>
package.json </br>

> #### Unmodified
> In this state the file has not been changed yet and nothing required to be done.
> #### Modified
> The file state differs from the last commit, but it is not yet "ready" to be committed.
> #### Staged
> The file has undergone modification and is now "ready" to be committed as the file moves to the following phase.</br>
> In this stage, for example file can be staged using ```javascript git add musoplan.js]```

**Note:** Regular use of ```git status``` shows if there is any uncommited changes left to be commited.

### Commits
Once required changes made, committing is necessary in order to be able to save the changes to repository. Below command is used for this purpose: </br>
```git commit -m "message"```

### Merges

When there are no conflicting changes to the same file, merging is the simplest situation possible. In this instance, all that is required is to check out to the destination branch of the merge and "merge in" the modifications from the source branch.<br/>

Below commands will take us to the main branch and merge changer from our coding branch: <br/>
```git checkout main``` <br/>
```git merge coding``` <br/>

### push/pull to share commits with remotes
In order to interact with the remote repository from local repository **pull** (get commits from a remote) and **push** (add commits to a remote) are used as well as few others as describe below: <br/>

```git remote -v``` : See what branches are available in the remore Repo <br/>
```git push origin``` : Pushing files created in local Repo to remote Repo<br/>
```git pull origin``` : Receiving files and from Remote Repo and updating local Repo<br/>

### pull requests

Once changes in local Repo is pushed to Remote Repo on Github, we create a new pull request in the "Puu requests" section of our Repo. Then out changes will be reflected in destination Repo after getting approved.

### commit log

We see log of previously committed gits using ```git log```

This repository was not forked from any other repository.

