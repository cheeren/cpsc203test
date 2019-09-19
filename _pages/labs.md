---
permalink: /labs/
title: "Lab General Instructions"
excerpt: "CPSC 203, Programming, Problem Solving, and Algorithms."
modified: 2019-09-18T16:39:37-04:00
author_profile: false
---

{% include base_path %}

# How to fetch and push code for lab

First, we want to create a fork of the lab repository:
 1. Go to https://github.students.cs.ubc.ca/cpsc203-2019w-t1
 2. Open the repository associated with the lab in consideration.
 3. Click the 'Fork' button on the top right. A fork is a copy of the someone else's repo to your own account.
 4. After the fork is created, github will take you to the fork of the repo.
 5. Click on 'Settings' - > "Collaborators & teams" and remove 'students' from the team.
 
Now, we want to 'clone' the repository to our machine to modify the code. There are two ways to do this:
 
 **Using PyCharm** 
 - If you are on the welcome page of PyCharm, click on 'Checkout from Version Control' -> 'Git'. Then from the 'URL' dropdown, select `https://github.students.cs.ubc.ca/[your_CWL]/[lab_repo].git` and click on 'Clone'.
 - If you are already within a project in PyCharm, click on 'VCS' from the toolbar and select 'Checkout from Version Control' -> 'Git'. Then from the 'URL' dropdown, select `https://github.students.cs.ubc.ca/[your_CWL]/[lab_repo].git` and click on 'Clone'.
 
 **Using Git CMD** 
 - **On MacOS**, open a terminal and navigate to the directory you want to clone your code in and enter `git clone https://github.students.cs.ubc.ca/cpsc203-2019w-t1/Lab_Initials.git`. Log in to github if needed.
- **On Windows**, open git bash and navigate to the directory you want to clone your code in and enter `git clone https://github.students.cs.ubc.ca/cpsc203-2019w-t1/Lab_Initials.git`. Log in to github if needed.

Now, we can start modifying the code. After making certain progress in our code, we can 'commit' and 'push' code to our github repo. This allows us to track changes in our code over different iterations of development. To do so:

 **Using PyCharm** 
 
 1. Click on 'VCS' -> 'Commit'. 
 2. Select the files that you would like to commit. PyCharm also shows the changes that you've made to the selected file by displaying the contents of the file before and after changes side-by-side. It is usually preferred to leave out temporary or cached files from github. PyCharm creates a hidden directory '.idea' to store information about displaying the project and varies from user to user. Hence, it should not be included in the commit. 
 3. After you've selected the files that you want to commit, you can specify a 'Commit Message' in its input text box. A commit message is a concise one-liner about what has changed since the last commit. For example, in the Initials lab it could be "Added a function to draw T". 
 4. Finally, click on the small inverted triangle besides the 'Commit" button and select "Commit and Push". 
 5. Hurrah! You've committed and pushed the changes to your repo. You can view your commits on your web-browser by clickong on 'commits' on the repo page. 
 
 
 **Using Git CMD** 
 
 1. While you in the directory which contains the repo in Git Bash on Windows or in a Terminal on MacOS, enter `git add space_separated_names_of_files_you_want_to_commit`. It is usually preferred to leave out temporary or cached files from github. An IDE might create temporary files in the directory that you are working in. For instance, PyCharm creates a hidden directory '.idea' to store information about displaying the project and varies from user to user. These files should not be included in the commit. 
 2. After you've selected the files that you want to commit, you can create a commit and specify a commit message by entering `git commit -m "commit_message"`. A commit message is a concise one-liner about what has changed since the last commit. For example, in the Initials lab it could be "Added a function to draw T". 
 3. Finally, you can enter `git push origin master` to push the commit to your repo. 
 4. Hurrah! You've committed and pushed the changes to your repo. You can view your commits on your web-browser by clicking on 'commits' on the repo page. 

