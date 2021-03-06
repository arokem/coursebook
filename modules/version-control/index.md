---
title: Version Control
layout: module
---

# Version Control

This module will introduce you to the workflows used with the popular version control system Git. The concepts learned in this module will be applied to the management of your personal project throughout the course.




## Learning Outcomes

Upon completion of this module you should be able to:

- Understand the benefits of an automated version control system.
- Understand the basics of how Git works.
- Configure git the first time is used on a computer.
- Understand the meaning of the --global configuration flag.
- Create a local Git repository.
- Go through the modify-add-commit cycle for single and multiple files.
- Explain where information is stored at each stage of Git commit workflow.
- Identify and use Git commit numbers.
- Compare various versions of tracked files.
- Restore old versions of files.
- Configure Git to ignore specific files.
- Explain why ignoring files can be useful.
- Explain what remote repositories are and why they are useful.
- Clone a remote repository.
- Push to or pull from a remote repository.
- Collaborate pushing to a common repository.
- Explain what conflicts are and when they can occur.
- Resolve conflicts resulting from a merge.
{:.learning-outcomes}






## Independent | Create a GitHub Account

Register and verify your GitHub account, ready for classroom use.

- [Slideshow: Creating a GitHub Account][github-setup]
- [Activity: Request to join course organisation (TODO)](#)
{:.resources}

[github-setup]: {{ site.slideshows }}/modules/version-control/creating-a-github-account




## Classroom | Introduction to Git

Introduction to the basics of Version Control, Git and GitHub.

**Schedule**

- [Lecture: Version Control Introduction][intro]
- [Activity: Install and Configure Git (Software Carpentry)][install]
- [Lecture: Repositories][repos]
- [Activity: Create a Repository (Software Carpentry)][create-repo]
- [Lecture: Git Workflow][wkflow-slides]
- [Activity: Tactile Git Workflow (TODO)](activities/tactile-git-workflow.html)
- [Activity: Shell Git Workflow (Software Carpentry)][sc-wkflow]
{:.resources}

[intro]: {{site.slideshows}}/modules/version-control/introduction
[install]: http://swcarpentry.github.io/git-novice/02-setup.html
[repos]: {{site.slideshows}}/modules/version-control/repositories
[create-repo]: http://swcarpentry.github.io/git-novice/03-create.html
[wkflow-slides]: {{site.slideshows}}/modules/version-control/git-workflow
[sc-wkflow]: http://swcarpentry.github.io/git-novice/04-changes.html


**Resources**

- [Version Control with Git (Software Carpentry)](http://swcarpentry.github.io/git-novice/)
- [Automated Version Control (Software Carpentry)](http://swcarpentry.github.io/git-novice/01-basics.html)
{:.resources}









## Independent | Practising Git Shell

Review the Git commands that you have learned by completing at least one of these online activities.

- [Learn Git (GitHub)](https://try.github.io)
- [Basic Git Workflow (Codecademy)](https://www.codecademy.com/en/courses/learn-git/lessons/git-workflow/exercises/hello-git)
{:.resources}




## Classroom | Everyday Git

Advanced functionality and commands using Git.

**Resources**

- [Exploring History (Software Carpentry)](http://swcarpentry.github.io/git-novice/05-history.html)
- [Ignoring Things (Software Carpentry)](http://swcarpentry.github.io/git-novice/06-ignore.html)
- [Remotes in GitHub (Software Carpentry)](http://swcarpentry.github.io/git-novice/07-github.html)
- [Collaborating (Software Carpentry)](http://swcarpentry.github.io/git-novice/08-collab.html)
- [Conflicts (Software Carpentry)](http://swcarpentry.github.io/git-novice/09-conflict.html)
- [How to Backtrack (Codecademy)](https://www.codecademy.com/en/courses/learn-git/lessons/git-backtracking/exercises/backtracking-intro)
- [Git Teamwork (Codecademy)](https://www.codecademy.com/en/courses/learn-git/lessons/git-teamwork/exercises/remotes)
- [Learn Git Branching](http://pcottle.github.io/learnGitBranching/)
{:.resources}





## Independent | Getting Around GitHub

Get familiar with GitHub by completing the following tasks.

_No tasks yet_




## Group Activity | Sharing Repositories

Practice collaborating with Git by completing this activity.

_No task yet_












## Additional Resources


- [Git Branching (Codecademy)](https://www.codecademy.com/en/courses/learn-git/lessons/git-branching/exercises/why-branch)
- [Open Science (Software Carpentry)](http://swcarpentry.github.io/git-novice/10-open.html)
- [Licencing (Software Carpentry)](http://swcarpentry.github.io/git-novice/11-licensing.html)
- [Hosting (Software Carpentry)](http://swcarpentry.github.io/git-novice/12-hosting.html)
{:.resources}




## Badges

1. ### Git Status and Logs
![Badge](images/badges/badge.png)
Given a git repository, can use git status and git log to answer questions about the number of commits, when they were made, what files are committed and what files are staged. 
_Learning outcomes: ?_

2. ### Ignoring files and folders
![Badge](images/badges/badge.png)
Given a git repository, can edit the config file to ignore all files of certain types, as well as all files contained within certain folders.
_Learning outcomes: ?_

3. ### Checking out branches
![Badge](images/badges/badge.png)
Use the log function, work out which branch to check out based on the commit comments, checkout a file, revert to the original branch, anc commit the file.
_Learning outcomes: ?_

4. ### What's Changed? Using diff
![Badge](images/badges/badge.png)
Using the log function, find out when a certain file was updated, then using diff work out exataly what changed over the different iterations. 
_Learning outcomes: ?_

5. ### Remotes in Git
![Badge](images/badges/badge.png)
Sketch outline. Have two remotes (representing two different colloboartors). Use a fetch command to get their commit history. Use diff to find out which file to commit based on some criteria, then commit that to your own branch.
_Learning outcomes: ?_

6. ### Collaborating with Git
![Badge](images/badges/badge.png)
Sketch outline. Working in pairs\group of three. Create a repository on Github. Add partners as a colloborator. First partner creates a readme file. Next partner(s) pull the fill and add content, then push it back to the remote. Now each partner introduces conflicts and the subsequent partner needs to resolve them.
_Learning outcomes: ?_
{:.badges}



