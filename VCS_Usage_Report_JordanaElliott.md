# VCS Usage Report
**Report Author:** Jordana Elliott  
**Report Version:** 1.0.1  
**Report Date:** 3rd of August 2022

## 1. Difficulties or Challenges During Development
Difficulties and challenges associated with Git, the distributed version control system (DVCS) used during the development of the MusoPlan application, were minimal overall. However, the challenges that did emerge included:  
* Practising commit consistency, such as only working on one major function at once, and remembering to commit once an acceptable draft was built.  
* Monitoring branch check-in – that is, ensuring that the correct branch was selected when adding, changing, and committing files and their respective changes.

## 2. How You Complied with the Organisational Requirements
Throughout the development of MusoPlan, I attempted to comply with the organisational requirements in the following ways:  
* All implementation file commits were conducted on the implementation branch. Branch check-in was confirmed by utilising the “git status” command to view which branch I was working on.  
* Commit messages:  
  * Were written in the standard past tense/imperative mood style.  
  * Strove to focus on changes made in one major function and/or file, and mostly adhered to a single change commit scope.  
* Each commit contained my GitHub Account Name (author name) and email address, allowing for identification of what changes I, as an author, had specifically implemented.

## 3. How You Verified the VCS was Performing as Expected  
I employed the following methods to verify Git’s performance:  
* **Branches:** Branch validation was achieved by using the git command “git status”, which when executed, references in its first line “On Branch …” which branch is being working upon.  
* **Stages:** Stage validation was conducted by using the “git status” command, which lists pre-staged files under the “Changes not staged for commit” header and staged files (by executing the “git add” command) under the header “Changes to be committed”.  
* **Commits:** Commit validation was approached by utilising the “git log” command. This command presents a log of all commits made using the “git commit -m” command.  
* **Merges:** Like commits, merges (made using “git merge”) were validated by employing the “git log” command (while in master branch) to ensure that they had been committed. Merged branch and master branch git logs were compared to ensure the merge was successful.  
* **Push/Pull:** Pushes (executed by “git push”) can be verified by checking the remote repository’s commit log, or applying the “git diff” command. Similarly, pulls can be validated by applying “git status” – if the current/local branch is behind on commits, the “git pull” command can be executed again.  
* **Pull Requests:** Pull requests can be validated in GitHub after reviewing requests and resolving their potential for file conflicts by explicit confirmation (of pull request acceptance) in the repository’s pull hub, and checking the repository’s commit log.  
* **Commit Log:** To validate the commit log, “git log” was executed. Assessing the log structure and identifying its key elements (Head location, author/email address, date/time, and commit message), as well as checking the most recent commits, can verify log performance.

## 4. If Your Repository was Forked from Another Repository, How Would You Go About Having Them Integrate Your Changes to the Central Repository?
I would go about having the owner of whose repository I have forked integrate my changes to their central repository by following these steps: 
1. Once I had made and committed my changes to the cloned (forked) repository (on a new branch) locally, I would push my changes to the new branch.
2. I would then locate the web page of the original repository on GitHub, and click the “New Pull Request” option.
3. In opening a new pull request, I would check which branches (of the original repository and my forked version) are being compared, and then add a title and comment in the request form about the changes that I wish to make to the owner’s central repository.
4. After submission, I would await further instruction, discussion, conflict resolution and/or implementation by the original repository’s author.