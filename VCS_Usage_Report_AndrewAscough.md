# VCS Use Report
In this report I will discuss:
- Difficulties and challenges faced when using the VCS
- How I complied with the organisational requirements.
- How the VCS was verified that it was performing as expected
- Integrating changes to the central repository after forking from another repository

## Difficulties and Challenges
I found using the VCS relatively simple at certain points through development, as I had some previous experience in using SVN which is similar to Git in how you can branch and push commits to changes you've made.

However, one primary part I found challenging was working out how much of a change would need to be made before pushing that change to the development branch. In the future I feel it would be more beneficial to me and the organisation if I made more commits with smaller changes, rather than trying to make one commit per major functionality being implemented.

## Complying with Organisational Requirements
Below is a list of the (summarised) organisational requirements for utilising the VCS as well as how this project met these requirements during its development lifecycle.
-  All development must be done with a well known VCS
   - The version control system (VCS) chosen for this project was GitHub, which is one of the most popular VCS programs out there.
-  All development must be done on feature branches and not on main/master
   - During the development process all commits and changes were made to a 'development' branch. 
-  All commit messages must follow the industry standard
   - All commit messages were written in present tense and imperative mood
-  Commit scope should be kept to individual changes
   - For every commit made there was only one feature change included in the changes.
-  All commits must be configured so each commit contains the author's name and email address
   - During the installation process for Github we used the following two commands to configure git to use our name and email on commit messages. (see Acitvity2/VCS_Report.md section: "Configuration Process" for more)
```bash
~$ git config --global user.email "emailAddress"
~$ git config --global user.name "githubUsername"
```

- All repositories must start with just a README.md file
  - The creation of the master branch for this project was initiated with just a README.md file as well as the associated default git items too.

## Verifying the Functionality of the VCS
In this section I will briefly outline how each of the following functionalities of GitHub were tested
### Branches
By creating a separate branch from master and changing something on the new branch (and committing + pushing) we should not be able to see anything has changed on the master branch, which can be verified on your github repository's webpage by switching between the branch views.
### Commits
We can determine that a commit has been successful by viewing the commit history and seeing that our changes are present.
### Merges
When merging two branches we can verify this has worked when we see the presense of one branch's changes that were previously not there. In this project I did this merge with this report document and the development branch.

### Push/Pull
To confirm that a push command works it can be as simple as checking that you have committed some changes on a branch and pushed to github, and the repository page for that change should be updated.

To confirm the pull command we can checkout our branch, make a change on a different computer and then pull on that other computer and it should update with our new changes
### Pull Requests
Just to test a pull request I'll be finishing this document on the VCSUsageReport branch and creating a pull request to add it to master. 

### Commit Log
As I have github desktop for Windows installed, viewing the commit log is very easy and each commit you make appears under the history tab next to the changes tab.


## Scenario
Question: *If your repository was forked from another repository, how would you go about having them integrate your changes to the central repository?*

To sync our respective forks we can use a pull request. This process will merge together our changes in our fork to the central repository that we wish to create a pull request for. To merge the pull request we first must make sure that there are no major conflicts between our changes and the central repository. A conflict is when a file has been altered in two different ways between two different forks. This will create a conflict as now Github will need to be told which of the two versions is the 'correct' one and which will be discarded. After working through all conflicts (if any) you can then have the owner of the central repository approve your changes to be merged into the central (or master/main) branch.