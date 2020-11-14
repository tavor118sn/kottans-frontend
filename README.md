# kottans-frontend

**Completed tasks:**

General
- [x] [Git Basics](#Git-Basics)
- [x] [Linux CLI, and HTTP](#Linux-CLI-and-HTTP)
- [x] [Git Collaboration](#Git-Collaboration)

Front-End Basics
- [ ] Intro to HTML and CSS
- [ ] Responsive Web Design
- [ ] JavaScript Basics
- [ ] Document Object Model

Advanced Topics
- [ ] Building a Tiny JS World
- [ ] Object oriented JS
- [ ] OOP exercise


## General

### Git Basics 

It was good to refresh the knowledge about git and different git commands.
git rebase definitely helps to keep git history clearer.


### Linux CLI and HTTP

I liked site about Linux because you can read theory and practice after that.
It has a good explanation about base commands, permissions, etc.
I would recommend this site to everyone who wants to learn Linux.

ALso information about HTTP was useful. But I would add a simple article about
REST API, to better understand where and how statuses and methods are used.

**Screenshots**

- [Linux-Tutorial-Quiz-1](task_linux_cli/Linux-Tutorial-Quiz-1-Linux-Survival.png?raw=true)
- [Linux-Tutorial-Quiz-2](task_linux_cli/Linux-Tutorial-Quiz-2-Linux-Survival.png?raw=true)
- [Linux-Tutorial-Quiz-3](task_linux_cli/Linux-Tutorial-Quiz-3-Linux-Survival.png?raw=true)
- [Linux-Tutorial-Quiz-4](task_linux_cli/Linux-Tutorial-Quiz-4-Linux-Survival.png?raw=true)

### Git Collaboration

* **what was new:** working with forked repository
```commandline
git remote add upstream https://github.com/udacity/course-collaboration-travel-plans.git
git fetch upstream master
# merge in Lam's changes
git merge upstream/master
# send Lam's changes to *my* remote
git push origin master
```
* **what was surprised:** -
* **what intend to use in future:** squashing the commits
```commandline
git rebase -i HEAD~3
```
use p or pick – to keep the commit as is  
use r or reword – to keep the commit's content but alter the commit message  
use s or squash – to combine this commit's changes into the previous commit (the commit above it in the list)

**Screenshots**

- [GitHub-Collaboration-Udacity](task_git_collaboration/GitHub-Collaboration-Udacity.png?raw=true)
- [Learn-Git-Branching](task_git_collaboration/Learn-Git-Branching.png?raw=true)

