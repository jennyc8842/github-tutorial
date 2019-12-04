# GitHub Tutorial

_by <Jenny Cheng>_

---
## Git vs. GitHub
**_Git_** is a system of version control primarily used by programmers and others who write code.
  **_Github_** is a website that allows you to upload your Git repositories online.


---
## Initial Setup
To make a github account, [first go to this link](www.github.com).
  Click sign up on the upper right corner and fill in the contents you need.
    [IDE](ide.cs50.io) stands for Integrated Development Environment and it is where you'll be doing your work and is main code editor for the rest of SEP.
---
## Repository Setup
1. Enter **mkdir <directory name>** (This is so we can make  a new directory to practice in)
2. Enter **cd <directory name>** (To make our new directory our working directory.)
3. Enter **git init** (Makes our current, empty directory into a fresh Git repository.)
4. Enter **touch README.md** (Creates a new README file (more on this later) We'll need README files often.)
5. Enter **c9 README.md** (Opens the new README file )
6. Type things into the README file
7. Enter **git add README.md** (Adds our new file to the staging area.)
8. Enter **git commit -m "<add message>"** (Makes our first commit using the README file, and writes a message indicating that this is what we did.)


---
## Workflow & Commands
When you save your file by doing _CTRL + S_, it is saving the changes you made into the file.
  When you _git add (filename)_, it adds the file into the repository.
    When you _git commit_, you are permanently saving the changes.
      When you _git push_, you have saved the changes to the repository and now it's on github.