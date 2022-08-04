# Difficulties or challenges during development -
* Github terminology is bit confusing for beginner.
* New users can find the many different options and ways of doing things in GitHub confusing and overwhelming.
* A bad merge is very difficult to revert.
* Overwhelming and intimidating when you start using it.
* If you’re new to GitHub, one of the challenges often talked about is getting to grips with the mental model, which eases with practice and time.

# How you complied with the organisational requirements
* You can control features that secure and analyze the code in your organization's projects on GitHub.
* You can review the permission levels for your organization's installed integrations and configure each integration's access to organization repositories.
* You can review the permission levels for your organization's installed integrations and configure each integration's access to organization repositories.
* GitHub and the Git workflow present their own set of security and compliance challenges that must be addressed by your organization’s compliance teams.
* Compliance requirements tend to be very particular about how services are accessed, who can access them, how that access is managed, and how it can be revoked when necessary. 

# How you verified the VCS was performing as expected, behaviours you should test and describe include-
Git can be installed on the most common operating systems like Windows, Mac, and Linux. 

Checking for Git-
To see if you already have Git installed, open up your terminal application.
* If you're on a Windows machine, open the windows command prompt or "Git Bash".
Once you've opened your terminal application, type git version. The output will either tell you which version of Git is installed, or it will alert you that git is an unknown command. If it's an unknown command, read further and find out how to install Git.

* We can create repositry in github account and then we can create clone on local computer. After that we can create a seprate featue branch for work implementation. Whatever we are doing in feature branch for example creating file, add them through git add filename and then commit them with commit comments. Then you can merge feature branch into main branch and puch your local work to origin which is your repositry on Github. 

* Then go to your Github account and open repositries. After that selct your repositry in which you pushed your work. If you are able to see all updated files in your repositry then it's mean VCS is performing as expected.

1. branches- 
Branches allow you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository.
In order to create a new Git branch, without switching to this new branch, you have to use the “git branch” command and specify the name of the Git branch to be created.

$ git branch <branch_name>

You can inspect existing branches by running the “git branch” command with the “-a” option for all branches.

$ git branch -a

$ git checkout -b <branch_name>

2. stages-
A staging step in git allows you to continue making changes to the working directory, and when you decide you wanna interact with version control, it allows you to record changes in small commits. we can see git status by-

git status

3. commits -
Similar to saving a file that's been edited, a commit records changes to one or more files in your branch. Git assigns each commit a unique ID, called a SHA or hash, that identifies:

The specific changes
When the changes were made
Who created the changes

git commit -m "commit message"

4. merges- 
The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch.
it merge will combine multiple sequences of commits into one unified history. In the most frequent use cases, git merge is used to combine two branches.

git merge branchname

5. push/pull to share commits with remotes-
Push: sends commits and asks them to update their branch. This requires that things be right on their end. This cannot combine parallel development.

Pull: runs git fetch, which gets commits and has your Git update your remote-tracking name, then runs a second Git command to update your branch. The second command can combine parallel development.

6.commit log-
Committing saves edits/changes to our GitHub repository. With GitHub, every commit you make has a specific signature/ID the keeps the record of the changes you have made.

# If your repository was forked from another repository, how would you go about having them integrate your changes to the central repository? 
Once I create a copy in our account through fork and made changes in that, then I can submit these changes as contributions to the original project.I need to create pull request and merge it and my fork is now updated successfully. 

# Refrences -

* https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow

* https://docs.github.com/en/get-started/quickstart/fork-a-repo

* https://www.section.io/engineering-education/how-to-sync-and-update-a-forked-repo/

* https://stackoverflow.com/questions/11240715/what-is-the-difference-between-git-push-and-git-pull#:~:text=Push%3A%20sends%20commits%20and%20asks,command%20to%20update%20your%20branch.

* https://smashinghub.com/understand-the-pros-and-cons-of-using-github.htm
