# Research on Version Control System VCS 

It is crucial to find a right system which allows your team to have a good track of changes for a project file. Therefore a research has been conducted by the team to seek the best option for controlling files and its versions which will be developped by coworkers at Globex Corporation. The research team has studied *10 types of version control systems* below that are currently popular on the market:

    1. GIT- majority of employees at Globex Corporation is familiar with this system.
    2. CVS
    3. Bitbucket
    4. SVN
    5. Mercurial
    6. Monotone
    7. Bazaar
    8. TFS 
    9. VSTS
    10. PERFORCE HELIX CORE
    
After long discussion with the team, we decided to use the Github by giving reasons that majority in our team is familiar with using Git and Git Products, and below given advantages:

* free
* efficient and fast performance 
* Compatible with existing systems and protocols like HTTP, FTP, ssh
* Capable of efficiently handling small to large sized projects
* Offers an amazing command line utility known as git bash.

While CVS has no integrity checking for source code repository, poor support for distributed source control and does not support signed revisions and merge tracking. Similarly enough, SVN, VSTS also do not support signed revision.

One of the main reasons developers like Git is its effective branching model. In Git, branches are only references to a certain commit. This makes them lightweight yet powerful. Git allows you to create, delete, and change a branch anytime, without affecting the commits. If you need to test a new feature or find a bug — make a branch, do the changes, and then delete the branch. Git supports the idea of a staging area, which is also known as the index file.
Staging is the practice of adding files for your next commit. It allows you to choose which files to commit next. This is useful when you don't want to commit all changed files together.
But Mercurial embeds the branches in the commits, where they are stored forever. This means that branches cannot be removed because that would alter the history. However, you can refer to certain commits with bookmarks, and use them in a similar manner to Git’s branches.

Helix Core is easy to use. (See how Helix Core's P4 commands compare to Git commands or Mercurial commands.) It provides stronger security options (including MFA, access control, and more) than Git or Mercurial. And it offers a better way to branch and merge (Perforce Streams). 

Git installation on Windows was easy enough providing below steps are provided:

### Step 1:

Download the latest version of Git and choose the 2.33.0 version. After the file is downloaded, install it in the system. Once installed, select Launch the Git Bash, then click on finish. The Git Bash is now launched.

### Step 2:

Check the Git version: by typing $git--version

### Step 3:

For any help, use the following command: $git help config

This command will lead you to a browser of config commands. Basically, the help the command provides a manual from the help page for the command just following it (here, it's config).


### Step 4:

Create a local directory using the following command: $mkdir test 

### Step 5:

The next step is to initialize the directory: $git init

### Step 6:

Go to the folder where "test" is created and create a text document named "demo." Open "demo" and put any content, like "Hello Simplilearn." Save and close the file.

### Step 7:

Enter the Git bash interface and type in the following command to check the status: $git status

### Step 8:

Add the "demo" to the current directory using the following command: $git add demo.txt

### Step 9:

Next, make a commit using the following command: $ git commit -m "committing a text file"

### Step 10:

Link the Git to a Github Account: $ git config --global user.username

### Step 11:

Open your Github account and create a new repository with the name "test_demo" and click on "Create repository." This is the remote repository. Next, copy the link of "test_demo."

### Step 12:

Go back to Git bash and link the remote and local repository using the following command: $ git remote add origin <link>
Here, <link> is the link copied in the previous step.

### Step 13:

Push the local file onto the remote repository using the following command: $ git push origin master

### Step 14:

Move back to Github and click on "test_demo" and check if the local file "demo.txt" is pushed to this repository.

In summary,  Git has features flexible enough to support all kinds of development processes, partially because its branches, by design, it is easier to follow.

    




