### Assignment_Activity05
#### Complete your VCS Report and send it to this repo via pull requests  

## VCS_Usage_Report_Wajhiha_Farooqui

# GIT Version Control Report

During developing process of "MusoPlan" application, while learning the GIT we have gained a good knowledge of how can we  use Git tools to track our files.
Tracking the files means,adding the files for commit and  allow us to choose which files to commit next. This is useful when you don't want to commit all changed files together and also we can also add all files together to save the time adding single fil at a time.

Git installation on Windows is easy to install The below steps are provided:

### Step 1:

Download the latest version of Git from this website "https://gitforwindows.org/"and choose the 2.37.2.2 version and start downloading. After the file is downloaded, install it in the system where you want to locate the file. Once installed, select Launch to start the Git Bash process and click on finish. The Git Bash is now launched oppens the GIT Bash terminal.

### Step 2:

Check the Git version: by typing the command "$"git--version" in the GIT Bash terminal that the GIT is downloaded sucessfully. If we run the above command it should show the latest version.

### Step 3:

For The help in the Github, we use the following command: $git help config

Git Help can be accessed from your Git Bash just by typing the command git help . Press Enter to execute the help command. This command will display all the information about Git. 

This command will lead you to a browser of config commands. Basically, the help command provides a manual from the help page for the command just following it (here, it's config).


### Step 4:

To make a new local directory we use the following command "$mkdir sample1" 

### Step 5:

After we make the directory the next step is to initialize the directory we use "$git init"

### Step 6:

Go to the folder where "sample1" is created and create a text document named "sample1." Open "sample1" and put any content, like "I'm Wajhiha" Save and close the file.

### Step 7:

Enter the Git bash terminal and type the following command to check the status in the git : $git status

### Step 8:

To Add the "sample1" file into the current directory use the following command: $git add sample.txt

### Step 9:

Next, make the first commit using the following command: $ git commit -m "committing message to the text file"

### Step 10:

Link the Git globally to a Github Account: $ git config --global user.username

### Step 11:

Open your Github account and create a new repository with the name "test_sample" and click on "Create repository." This is the remote repository. Next, copy the link of "test_sample."

### Step 12:

Go back to Git bash and link the remote and local repository using the following command: $ git remote add origin <link>
Here, <link> is the link which we can copy from the previous step.

### Step 13:

Push the local file into the remote repository using the following command: $ git push origin master

### Step 14:

Move back to Github and click on "test_sample" and check if the local file "sample1.txt" is pushed to this repository.

In summary,  Git has features flexible enough to support all kinds of development processes, because its branches and design is easier to follow.