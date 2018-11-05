# Intro to Git Workshop: Home

## Intro to Git: Description

This guide provides additional resources to supplement the hands-on Intro to Git Workshop offered at the UNC Libraries: learn how to use Git, one of the most popular version control systems in the world. You don't have to be a developer to git started!

The last workshop was taught on [Wednesday, October 3, 2018](https://calendar.lib.unc.edu/event/4386938) at Davis Library Research Hub.

#### Prerequisites:

1. [Download and install the latest version of Git](https://git-scm.com/downloads)

2. [Create a free GitHub account](https://github.com/)

#### Slides:

* [Git Intro](https://unc-libraries-data.github.io/Intro-to-Git/Intro%20to%20Git.pdf): This slide deck was presented during the 10/3/2018 git intro workshop. Exercises are adapted from Library Carpentry's [Git Intro for Librarians](https://librarycarpentry.github.io/lc-git/) lesson.

## Basic Git Commands Cheatsheet

### Setting up Git

`$ git config --global user.name "Mona Lisa"`

_Sets your username in Git; can be different than GitHub username_

`$ git config --global user.email "example@example.com"`

_Sets your email address in Git; should be same as GitHub email address so GitHub can associate your commits with your account_

### Creating Git Repositories

`$ git init`

_Turns any folder into a Git repository_

`$ git clone https://github.com/`_username_`/`_repo-name_`.git`

_Copies an existing repository to your computer_

`$ git remote add origin https://github.com/`_username_`/`_repo-name_`.git`

_Links your local repository with your remote repository_

### Making Changes

`$ git status`

_Returns status of changed files in your git repository_

`$ git add index.md`

_Adds changes made to a given file or set of files (index.md in this example) to your staging area_

`$ git commit -m "Add index.md"`

_Saves a snapshot of changes with a summary message_

`$ git push origin master`

_Syncs commits from your local repository up to your remote repository_

`$ git log`

_Returns list of local commits, or a history of saved snapshots_

`$ git pull origin master`

_Syncs commits from your remote repository down to your local repository_



### Bonus

`$ git diff`

_View unstaged changes made to all files in your git repository_

`$ git remote add upstream https://github.com/`_original-owner_`/`_original-repo-name_`.git && git pull upstream master`

_Syncs your forked repository to the original repository. For more information, see GitHub's [Configuring a remote for a fork](https://help.github.com/articles/configuring-a-remote-for-a-fork/)._

## Other Resources

### More Tutorials:

* [Learn Git on CodeAcademy](https://www.codecademy.com/learn/learn-git)
* [Git Training and Tutorials on Lynda.com](https://www.lynda.com/Git-training-tutorials/1383-0.html) (free access provided via [UNC onyen-login](https://software.sites.unc.edu/lynda/))

### Tools:

* [SourceTree:](https://www.sourcetreeapp.com/) a free Git GUI that offers a visual representation of your repositories without having to use the command line

### Other Resources:

* [Library Carpentry](https://librarycarpentry.org/): list of available lessons created by the Library Carpentry community, which provides software and data skills training aimed at the needs and requirements of library professionals

* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet): quick reference for Markdown language

* [GitHub Help](https://help.github.com/)

	* GitHub's [Git Cheatsheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet/): even more Git commands!

* [Git Documentation](https://git-scm.com/doc):
	
	* [Pro Git](https://git-scm.com/book/en/v2) book by Scott Chacon and Ben Straub: gives in-depth, but easy-to-understand explanations of version control and the Git workflow
	
* [GitHub Pages Documentation](https://help.github.com/categories/github-pages-basics/)
