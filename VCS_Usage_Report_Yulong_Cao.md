### Activity 5 - VCS use report

Author: Yulong Cao
Date: 03/08/2022

Difficulties or challenges during development:

In general, my experience with utilizing the Git VCS for the MusoPlan development was good and no issues occurred.

Compliance with organisational requirements:

I complied with the organisational requirements by:
• Choosing the right distributed VCS - Git
• Start with a README.md file when initializing the repository
• Conducting different workloads and developments on designated feature branches
• Adding meaningful message when committing
• Making sure that all commits were limited to a single change

How I verified the VCS was performing as expected:

● Branches:
2 branches created for this project. One is addingDocs for documentations, the other is for implementation.

● Stages:
Files were staged using the git add <filename> command.
The git status command was used to make sure that the correct files were staged before commit.

● Commits:
Making commits is a common practice in this project by using git commit -m "meaningful message" to save changes made to a file to the local repository.

● Merges:
I used merge during development of a feature branch and when feature is done and committed I merge the branch into the main branch.

● Push/pull to share commits with remotes:

git push – sending all local files and docs to remote repo.
git pull – downloads contents from remote repo to local repo.

● Pull requests:
pull request will be used for the final stage of this program – sending the whole documents and code package for submission.

● Commit log:
using git log to demonstrate commit logs. It is a handy tool to review and read a history of everything that happens to a repository.

If your repository was forked from another repository, how would you go about having them integrate your changes to the central repository?

First, I need to make sure all local changes are updated and then push it to Github repo. When the first process is finished, a pull request must be sent to the creator of the repository that was forked from. To do this, just go to Github Repo and choose ‘Open a Pull Request’ to make a pull request by adding pull request message. Next, waiting for permission from the author of this repo before it can be merged.
