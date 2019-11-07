---
layout: post
title: "GIT LEARNING" 
subtitle: "github guide"   
feature-img: "assets/img/pexels/computer.jpeg"                    # Will display the image in the post
img: "assets/img/portfolio/cake.png"                    # Will display the image in the portfolio page
thumbnail: "assets/img/thumbnails/desk-messy.jpeg"
date: 2019-11-1                                          # Not mandatory, however needs to be in date format to display the date
#hide: true                                               # Prevent the page title to appear in the navbar
icon: "fa-search"                                        # Will Display only the fontawesome icon (here: fa-search) and not the title
tags: [sample,GIT]
---



### INSTALL GIT

GitHub provides desktop clients that include a graphical user interface for the most common repository actions and an automatically updating command line edition of Git for advanced scenarios.

##### GItHub for windows
<https://windows.github.com>

##### GitHub for Mac
<https://mac.github.com>

Git distributions for Linux and POSIX system are  available on the offical Git SCM web site.
    
    
##### GitHub for All Platforms
<http://git-scm.com>

### CONFIGURE TOOLING
configure user information for all local repositories

##### $ git config --global user.name "[name]"
Sets the name you want attached to your commit transactions

##### $ git config --global user.email "[email address]"
Sets the email you want attached to your commit transactions

##### $ git config --global color.ui auto
Enables helpful colorization of command line output

******

### CREATE REPOSITORIES
Start a new repository or obtain one from an existing URL

##### $ git init [project-name]
Creates a new local repository with the specified name

##### $ git clone [url]
Downloads a project and its entire version history

******

### MAKE CHANGES
Review edits and craft a commit transaction

##### $ git status
Lists all new or modified files to be committed

##### $ git diff
Shows file differences not yet staged

##### $ git add [file]
Snapshots the file in preparation for versioning

##### $ git diff --staged
Shows file difference between staging and the last file version

##### $ git reset [file]
Unstages the file, but preserve its contents

##### $ git commit -m "[descriptive message]"
Records file snapshots permanently in version history

*****


### GROUP CHANGES
Name a series of commits and combine completed efforts

##### $ git branch
Lists all local branches in the current repository

##### $ git branch [branch-name]
Creates a new branch 

##### $ git checkout [branch-name]
Switches to the specified branch and updates the working directory

##### $ git merge [branch]
Combines the specified branch's history into the current branch

##### $ git branch -d [branch-name]
Deletes the specified branc

******
  
  



