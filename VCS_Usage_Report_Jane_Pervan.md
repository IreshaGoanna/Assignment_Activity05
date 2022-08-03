# Use and Management of Git in the Development of the Musoplan App

### 1. Difficulties or Challenges During Development

 There were no challenges or difficulties experienced and, as such, version control was completed smoothly and efficiently in accordance with Globex’s organisational requirements.

### 2. Compliance with VCS Organisational Requirements during development

During development, changes were committed to the implementation branch after completion of each unit feature as well as whenever an existing feature was updated.  Additionally changes were committed after the creation and upon each update of each of the classes.  Documentation was committed to a separate branch upon finalisation.

### 3. VCS Verification

1.  Branches
    
    Two branches were created - one for the documentation (` and one for the implementation of the Musoplan app.  Both branches were successfully merged to the main upon completion of development and manual testing.
    
2. Stages
    1. All of the files that are included within the Musoplan app moved between unmodified and modified during development and were staged each time they were ready to be committed in accordance with Globex’s VCS requirements.  Files were staged using the `git add <filename>` command from the command line.  The `git status` command was used to double check that the correct files were staged before each commit.
3. Commits
    
    Files changes were committed to the implementation branch using the `git commit -m "present tense imperative mood statement"` command from the command line.  The included message provided the name of the function that was created or was updated.
    
4. Merges
    
    Upon finalisation of development and documentation each branch was merged with the main branch.  First the main branch was accessed using the `git checkout main` command.  Then the two branches were merged by typing `git merge implementation` and `git merge documentation`.  The merge was checked using `git status` and was then committed using `git commit -m "merge documentation to main` and `git commit -m "merge implementation to main`.
    
5. Push/Pull to share commits with remotes
    
    Using `git remote -v` to locate the source URL with the shortname `origin` a remote repository can be accessed using `git remote add` with the source URL.  Then using `git push <remoteURL> <mainbranchname>` the local branch can be sent to the remote repository for submission. This can then be double checked using `git remote show` `<URL shortname>`.  If further changes need to be included from the remote repository, these can be accessed using `git  pull remoteURL`.
    
6. Pull Requests
    
    Using `git push <remoteURL> <main>` the Musoplan app was sent to the Globex remote repository for final submission.
    
7. Commit Log
    
    The commit log can be accessed using the `git log` command in the command line.  The log is correctly displaying each commit within the implementation branch and within the documentation branches.  It also records the merges back to the main and the push.
    

### 4. Process for having changed integrated to the central repository, if forking is required

Once all of the necessary changes have been made to the fork, the fork is pushed to Github, then select the `compare and pull request` button and include a message detailing the changes included within the fork.  The official repository will review the request and determine whether to pull the fork into the official repository.