# kottans-frontend

**Completed tasks:**

General
- [x] [Git Basics](#Git-Basics)
- [x] [Linux CLI, and HTTP](#Linux-CLI-and-HTTP)
- [x] [Git Collaboration](#Git-Collaboration)

Front-End Basics
- [x] [Intro to HTML and CSS](#Intro-to-HTML-and-CSS)
- [x] [Responsive Web Design](#Responsive Web Design)
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

**what was new:** working with forked repository
```commandline
git remote add upstream https://github.com/udacity/course-collaboration-travel-plans.git
git fetch upstream master
# merge in Lam's changes
git merge upstream/master
# send Lam's changes to *my* remote
git push origin master
```
**what was surprised:** -
**what intend to use in future:** squashing the commits
```commandline
git rebase -i HEAD~3
```
use p or pick – to keep the commit as is  
use r or reword – to keep the commit's content but alter the commit message  
use s or squash – to combine this commit's changes into the previous commit (the commit above it in the list)

**Screenshots**

- [GitHub-Collaboration-Udacity](task_git_collaboration/GitHub-Collaboration-Udacity.png?raw=true)
- [Learn-Git-Branching](task_git_collaboration/Learn-Git-Branching.png?raw=true)

## Front-End Basics

### Intro to HTML and CSS

**what was new:** 
* some new tags from HTML5 
    * `<nav>`
    * `<header>`
    * `<main>`
    * `<footer>`
    * `<section>`
    * `<article>`
    * `<figure>`
    * `<figcaption>`
    * `<small>`
* `<datalist>` input
* `grid` and `flex` CSS

**what was surprised:** 
* CSS transitions 
  
**what intend to use in future:** 
* developer tools
* new tags and CSS

**Screenshots**
- [Intro-to-HTML-and-CSS-Udacity](task_html_css_intro/Intro-to-HTML-and-CSS-Udacity.png?raw=true)
- [Learn-HTML-Codecademy](task_html_css_intro/Learn-HTML-Codecademy.png?raw=true)
- [Learn-CSS-Codecademy](task_html_css_intro/Learn-CSS-Codecademy.png?raw=true)


**Useful links:**
* [HTML Cheat Sheet](https://www.codecademy.com/learn/learn-html/modules/learn-html-elements/cheatsheet)
* [CSS Cheat Sheet](https://www.codecademy.com/learn/learn-css/modules/learn-css-selectors-visual-rules/cheatsheet)


### Responsive Web Design

**what was new:** 
* viewport
* media-queries
* breakpoints



**what was surprised:** 
  
  
**what intend to use in future:** 
* flex and media-queries


**Screenshots**
- [Responsive-Web-Design-Fundamentals-Udacity](task_responsive_web_design/Responsive-Web-Design-Fundamentals-Udacity.png?raw=true)
- [Flexbox-Froggy](task_responsive_web_design/Flexbox-Froggy-Игра-для-изучения-CSS-Flexbox.png.png?raw=true)



**Tips**
* Width 100% is always relative and therefore responsive.
```css
img, embed, video {
  max-width: 100%;
}
```
* max-width actually overrides the width
* 125 pixels is pretty much smaller than any device, 
so logo 125 px will actually work well and be responsive.
* Tap targets should be bigger than the average finger. 
So, to ensure that all of your elements are at least that size, 
add min-height: 48px; and min-width: 48px; to every tappable element.  
height and width alone can be a little dangerous because 
it won't allow the element to resize 
if the content inside of it is bigger than the container.
* 2 breakpoints for different width
* 65 characters per line - optimal length

