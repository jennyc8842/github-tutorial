# GitHub Tutorial

_by Jenny Cheng_

---
## Git vs. GitHub

**_Git_** is a system of version control mostly used by people who program and code.
**_Github_** is a website that allows you to send your Git repositories on the internet.
The difference between both of them is that **_Git_** is a tool to manage your code history while **_GitHub_** is a hosting service for Git repositories.


---
## Initial Setup
* To make a github account, [first go to this link](https://github.com/).
* Click sign up on the upper right corner.
* Fill in the contents you need.
* If you're a student of HSTAT, you enter in your hstat gmail **except for the @hstat.org** (ex: jennyc8842).
* If you're _NOT_ a student of HSTAT, you can make up the username.
* After that, you make a password that you are able to remember.
* Fill any further details and click 'Create Account'
* [IDE](ide.cs50.io) stands for Integrated Development Environment and it is where you'll be doing your work and is main code editor for majority of programmers.
---

## Repository Setup
1. Go to your [IDE](ide.cs50.io)
2. Sign into your IDE account
3. On another tab of your browser, go to [Github](https://github.com/)
4. Sign into your github account
5. On the github page, go click the *+* icon on the top right corner
6. Then, click _New Repository_
7. Enter in the name of your repository
8. Click _Create repository_
9. Copy (CTRL + C) the 2 codes (should say **git add remote (link to your repository in SSH format)** and **git push -u origin master**) _We will paste this later on!_
10. Go back to your IDE tab
11. Enter in **mkdir (directory name)** _(Makes  a new directory)_
12. Next, type **cd <directory name>** _(Changes to the directory you specify)_
13. After that, type **git init** _(Makes a git repository)_
14. Then, type **touch README.md** _(Creates a file called 'README.md')_
15. Next, type **c9 README.md** _(Opens up the README file)_
16. Type things into the README file.
17. Then, go back to the terminal and enter in **git add README.md** _(Adds the file, README.md to the staging area)_
18. After that, type in **git commit -m "(add message)"** _(Makes a commit that stores the changes, and a message along with it to know what you did)_
19. Paste the 2 codes you copied earlier.
20. Enter in your username of github.
21. Enter in your password of github.
22. You're done!

---
## Workflow & Commands
When you save your file by doing _**CTRL + S_**, it is saving the changes you made into the file. Do this **every** time you made a change to the file!
  When you _**git add (filename)**_, it adds the file to the staging area. Use this when you made a change in the README file.
    When you _**git commit**_, you are adding the file and changes you made to your repository. Use this after when you _git add (filename)_!
      When you **_git push_**, you are transfering any changes from local repo up to the remote repo. Use this when you save, add and committed.