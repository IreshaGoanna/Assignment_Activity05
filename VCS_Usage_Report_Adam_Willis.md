## VCS USAGE REPORT

### Difficulties During Development

From a version control point of view I found git and the GitHub platform to be a steep learning curve. For instance the management and navigation of branches was a times difficult with little to no experience techniques required. Further, I found navigating the GitHub platform quite tedious between writing code and switching mind set through to make commits.  

### How I complied with the organisational requirements

Globex Corporation policy to use the distributed version control system Git was helpful. While, I stated above steep learning curve required I saw many benefits to using the system to control production code for the MusoPlan project.  While there a many Git technology platforms on the market, such as Git lab and GitHub the latter platform was a wise choice due to it’s large community of developers, training and support. 

In terms of compliance with Globlex Quality Assurance Polices the Business Automation Team completed the following: 

1. Used Git and GitHub as its main repository, and configuration was completed prior to commencing the development phase. 
2. Remote Origin was set up and Master was change to Main to comply with GitHub polices to commit. 
3. Further, regularly making commits included time, email and useful commit messages. 
4. Once was adds and commits were complete the team merged and pulled as required.

### How I verified the VCS was performing as expected

Generally, Git performed as expected, and when difficulties arose the git documentation, stack-over flow and communities provided and answers overcome the problem. 

To verify work was being committed regularly the team often checked to git log files to ensure commits had been made.  Git status was a regularly used to ensure changed had been staged correctly and git log for the committed snapshots. 

Merging production branches created throughout the project wasn't completed until the end of the development phase. Once merged  to share commits the with remote the the automation team used the push origin -upstream <.file> to sync up the project online.

### Forking from Another Repository

To ensure other team members can collaborate on this project requires some set up on GitHub’s platform. From the repositories settings Access can be granted to the developers required to work on the project. 

Once completed the team members add can all use the git clone command to make a copy of the repository currently sitting on the server. 

It would we wise for new collaborators to work on a new branch using git branch new in this manner no team members and making changes to the main trunk on the remote. Once the branch is checked out changes to the code can begin. git status will check the changes to files and git add <.filename> along with git commit -m “message”. For the team members to receive the change pushes are need to the remote so others can see the changes. Once the team is happy with code received from other member a pull request can be created from the creator of the branch.

The pull request is saying “I consider this feature branch complete” please merge to the main branch at your earliest convenience.

After this it is up to the lead programmer accept this request of reject the changes as required.