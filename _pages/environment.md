---
permalink: /environment/
title: "Programming Environment"
excerpt: "CPSC 203, Programming, Problem Solving, and Algorithms."
modified: 2019-09-18T16:39:37-04:00
author_profile: false
---

{% include base_path %}


# Configuration

One of the objectives of this course is for you to be able to extend your programming knowledge to solving real world problems, and a great way to get started with this is to have your own development environment set up on the machine you plan to use this semester.

We will first be using **Anaconda** which will set up multiple python "environments". A python environment is an instance of a version of python (python comes in two base versions 2 and 3 with further divisions, but for this course we will be using python 3) and includes additional libraries or "modules" (which will make our lives so much easier). After setting up Anaconda, we will set up an environment with the libraries we need for the first couple of weeks (it is possible to add or remove libraries at a later stage very easily).

Then, we will install **PyCharm** which is an industry leading IDE for python. Then we will set up **Git** in PyCharm. Of course, if you have a preferred IDE, you can go ahead and use that. Just make sure it's configured to the correct Git account.

For more information about what an IDE exactly is, follow this link https://www.codecademy.com/articles/what-is-an-ide and for what Git and Github is, follow this link https://codeburst.io/git-and-github-in-a-nutshell-b0a3cc06458f

## 1. Setting up Anaconda

**Windows:**

 1. Download Anaconda (Python 3.7 version) for Windows from https://www.anaconda.com/distribution/#download-section
and proceed with the setup with the default selections.
 2. Run Anaconda Navigator from the Start Menu.
 3. Click on the "Environments" tab on the left.
 4. Click on the "Create" button at the bottom of the list of environments.
 5. In the pop up box, choose a name for your environment. We will be using the name *pylove*. Python will be checked by default. Select 3.7 from the dropdown next to it, and click on "create". Wait until Anaconda initializes the new environment.
 6. Now run Anaconda Prompt from the start menu.
 7. Type in `conda activate pylove` and press enter. This is a way to switch between different environments. We switched from base to pylove as is evident in brackets on the command line.
 8. Now we will install the libraries we need to use. `conda install *library_name*` will allow us to do so. `conda install pandas beautifulsoup4 requests` will install pandas and beautifulsoup and their dependencies that we will require in the first few weeks.

**MacOS:**

(these didn't work for ckh)
 1. Download Anaconda (Python 3.7 version) for MacOS from https://www.anaconda.com/distribution/#download-section and proceed with the setup with the default selections.
 2. Run Anaconda Navigator from Launchpad.
 3. Click on the "Environments" tab on the left.
 4. Click on the "Create" button at the bottom of the list of environments.
 5. In the pop up box, choose a name for your enviroment. We will be using the name *pylove*. Python will be checked by default. Select 3.7 from the dropdown next to it, and click on "create". Wait until Anaconda intialises the new environment.
 6. Now run Anaconda Prompt from the start menu.
 7. Type in `conda activate pylove` and press enter. This is a way to switch between different environments. We switched from base to pylove as is evident in brackets on the command line.
 8. Now we will install the libraries we need to use. `conda install *library_name*` will allow us to do so. `conda install pandas beautifulsoup4 requests` will install pandas and beautifulsoup and their dependencies that we will require in the first few weeks.

## 2. Setting up PyCharm

**Windows:**
1. Download PyCharm Community Edition for Windows from https://www.jetbrains.com/pycharm/download/#section=windows
and proceed with the setup with the default selections.
2. Run PyCharm from the Start Menu.
3. Click on "Configure" on the bottom right corner and click choose Settings from the drop down.
4. Click on "Project Interpreter".
5. Click on the gear next to the list of Project Interpreter and select "Add".
6. Choose "Conda Environment".
7. Select "Existing Environment". Check if the Interpreter is being chosen from some path leading to envs\pylove\python.exe. If not, modify the path to math the environment that you created.
8. Check mark "Make available to all projects".
9. To set up git, click on "Version Control" from the options on the left.
10. Select "GitHub" from the sub-menu.
11. Click on Add account.
12. In the pop-up box, change Server to "github.students.cs.ubc.ca" and enter in your CWL username and password.
13. Click on "OK". We're all set !

**MacOS:**

1. Download PyCharm Community Edition for Windows from https://www.jetbrains.com/pycharm/download/#section=mac
and proceed with the setup with the default selections.
2. Run PyCharm from Launchpad.
3. Click on "Configure" on the bottom right corner and click choose Settings from the drop down.
4. Click on "Project Interpreter".
5. Click on the gear next to the list of Project Interpreter and select "Add".
6. Choose "Conda Environment".
7. Select "Existing Environment". Check if the Interpreter is being chosen from some path leading to envs\pylove\python.exe. If not, modify the path to math the environment that you created.
8. Check mark "Make available to all projects".
9. To set up git, click on "Version Control" from the options on the left.
10. Select "GitHub" from the sub-menu.
11. Click on Add account.
12. In the pop-up box, change Server to "github.students.cs.ubc.ca" and enter in your CWL username and password.
13. Click on "OK". We're all set !

