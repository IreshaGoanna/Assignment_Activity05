
# VCS Usage Report




## Difficulties or challenges during development

As I have used Git in previous projects I didn't experience any issues during development with VCS. The only issue is that I am used to
regularly pushing my changes to Github after committing a file so I had to catch myself from pushing my changes until the project was completed.

#


## How you complied with the organisational requirements

Muso Plan was developed using git a distributed version control system. All coding development was performed on a feature_branch as opposed to the main. Documentation was also committed on a separate documents branch. Commit messages were descriptive and were used when particular functions had been completed or if an edit to an exisitng function was made. Commit messages include the authors name and email address.

 #




## How you verified the VCS was performing as expected, behaviours you should test and describe include


I regularly used VS Code Source Control to ensure my commits had been added. Before starting a new task I would ensure that I was on the correct
branch and using git checkout to change when required. Before adding files I would run a git status to see file changes ready to be staged. I would then use git add . to stage files. I would run git status again to make sure all the files that have been edited have been staged for commiting. I would then run git commit -m and pass a message explaining the changes in my commit message. After completion of all the Software
requirements for the project. I merged my feature branch into my main as well as my document branch. Checked to make sure all my files came through. Once all files were located in the main branch of my local repository I used git push origin main to push my repository to my Github remote. Once on the Github remote other authorised users can download a copy of the repository to their local machine. Make changes and push to back to the Github remote. From here if I wanted to have the changes updated on my local machine I could run git pull to update the changes on my local repo. If the repository was forked from another repository I would need to clone the forked repo to my local machine. Then make changes on my local repo. Push the changes to the forked repo. Then I would need to create a pull request which would be sent to the user of the original repository to approve and merge my changes. 


#