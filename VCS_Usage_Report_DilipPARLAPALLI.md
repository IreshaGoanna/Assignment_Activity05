# Activity5

Created: August 3, 2022 11:03 AM

# Activity 5

## Git

For developing the Musoplan software I used Git which is the most popular and widely used version control system today. 

Gits is distributed version control system and installs locally on computer. It is a free and open-source command-line tool. 

The installation of Git is straight forward. It can be downloaded from the Git website based on the OS (Windows, Mac, Linux). Once downloaded, follow the instructions as provided in Git setup wizard screen until installation is completely. Open command prompt on windows and type git version to verify if Git was installed. 

git —version is the command used to check the latest version

## Difficulties or challenges during development

- Creating branch and checking out to that branch - As I’m still new to Git, sometimes I forget to create branch and work on main. I had restart and create a branch. I also have to make sure I checkout to that particular branch. If you have more than one branch , making sure i’m in the correct branch is important and it needed bit of practice.
- Adding and committing the file: Another challenge I faced  is adding the files to local repository and commit. When I made error committing message, I have to add the file again and commit to correct the message.
- Even though I can perform pull request successfully, I’m still facing difficulties in reviewing them. after each pull request.

## How I complied with the organisational requirements

- Created repository on GitHub ,cloned to git and added the repository on local system.
- Installed required packages on main and created branches for documentation and coding.
- Added files to Git one at a time and commit messages followed industry standard.
- I started repository with only Readme.md file without any source code.

## How I verified the VCS was performing as expected

- **Branches -** created two separate branches without disturbing the main. In one branch created and saved all the documentation and in the second branch I have only Javascript coding. In this way I felt like there won’t be any confusion later, while working on those files.
- **Stages -** The staging area helped me to keep track of all the files which are to be committed. Staging gave me control over which files needs to be committed. Every time I made changes to the file or created a file, I added it one at a time.
- **Commits** -  I performed commit each time I added the file with a meaningful message to indicate what code changes were done in that particular commit. Adding clear messages to each commit, it was easy for me to see what has changed and when the change happened.
- **Merges -**  I created and developed the software in the branches and once finalised the development, merged to the main branch, so everything will be in the main branch.
- **Push/pull to share commits with remotes -** I used push/pull to interact and sync my local repository and gitHub repository.
- **Pull requests -** Pull request let me tell my peers about changes I pushed to a branch in a repository on GitHub. After opening a pull request, I can discuss and review the changes with collaborators and add follow-up commits.
- **Commit log** - The commit log helped me go through the history of committed changes with in the repository. I was able to check when commits were made in each branch and see the commit message.

## If my repository was forked from another repository, how would I go about having them integrate my changes to the central repository?

To make changes the central repository after forking. I would clone to the repository to the local system. Create branches and work inside the branches, so main will not be disturbed. Once finished, add and commit the changes. Then merge with the main repository and push to the origin. Once it is in my repository I forked, I will initiate pull request to integrate the changes to the central repository and wait for it be to reviewed and also for any feedback, queries before  getting merged