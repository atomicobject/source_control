!SLIDE center
![Atomic Object](AO-wordmark-color.png)

!SLIDE subsection
<link href='http://fonts.googleapis.com/css?family=Comfortaa:400,700' rel='stylesheet' type='text/css'>
# What is Source Control #

!SLIDE bullets incremental
* "Revision control"
* "Version control"
* "Software configuration management"

!SLIDE incremental bullets
# Wikipedia
* "The management of changes to documents, programs, and other information stored as computer files."
* *yawn*

!SLIDE
# Stuffy terms, wrong focus #

!SLIDE bullets incremental
# Our definition: #

* "Process and tools to obtain the latest code for your project, then merge and store your changes in the code repository"

!SLIDE center
# Choices
![Subversion, Git, Mercurial, Darcs](sc_logos.png)

!SLIDE
# Today: Subversion
![svn](subversion.jpg)

!SLIDE bullets
![git](oreilly_git.jpeg)
# Later: Git
* (We use it a lot)

!SLIDE subsection
# Significance in software development

!SLIDE incremental
# Source control is
* Pervasive, intrinsic
* Ubiquitous but varied

!SLIDE bullets incremental
# Code goes in SC.
* *Always.*

!SLIDE incremental
# Why?
* Store and backup code
* Collaborate
* Track and document

!SLIDE incremental
![db](drobo.png)
# Backups aren't good enough

!SLIDE
![cats](socialite.jpg)
# The rest of the world

!SLIDE
# Publish

* SourceForge
* Github
* Google Code

!SLIDE incremental
# Share

* solicit input, feedback, criticism
* patches, forks, pull requests

!SLIDE subsection
# How Atomic uses source control

!SLIDE incremental bullets
# All code is in source control
* In-house Gitorious server
* Older SVN repositories 
* (still use both systems)

!SLIDE bullets
# All code is under CI
* (Continuous Integration)
* Watches our repositories for changes
* No SC => No CI

!SLIDE incremental bullets
# All repos available to all employees
* ...and sometimes the customer
* Web tools for discovering and exploring repos

!SLIDE incremental bullets
# Prefer command-line tools
* SVN and Git have some nice GUI interfaces
* Sometimes handy for odd cases, conflicts, etc
* ...but we use these tools SO MUCH

!SLIDE incremental bullets
# Always up-to-date
* You have the latest code to work on
* ...so do your coworkers
* (Don't be stingy)
* Punching out with uncommitted code is a NO NO

!SLIDE incremental bullets
# Not just for "code"
* Sales proposals
* Invoices and POs
* Electronic books

!SLIDE incremental bullets
# Personal use
* We all have repos
* Intra-office collaboration (RSS!)
* Games
* Language / tool exploration

!SLIDE bullets
# Atomic OSS
* http://github.com/atomicobject
* (SourceForge / RubyForge)

!SLIDE subsection
# Subversion
## A day in the life

!SLIDE
# svn st #

!SLIDE
# svn up #

!SLIDE 
# (edit code) #

!SLIDE 
# svn diff #

!SLIDE 
# svn up (again) #

!SLIDE 
# svn commit -m#

!SLIDE 
# svn up (later) #
* Nice clean merge

!SLIDE 
# svn up (more later) #
* Conflicts



!SLIDE 
# Conflict Resolution #
* Look for conflict markers
* Edit code
* Commit

!SLIDE incremental bullets
# Fancy stuff?
* Branching
* History
* Revert

!SLIDE incremental bullets
# (Not today)

!SLIDE subsection center
![collabcats](collabcats.jpg)
# Git
Our other first choice

!SLIDE 
# Git Advantages
* TODO

!SLIDE 
# Git = Independence
* no network, no server, no perms
* TODO moar?

!SLIDE subsection
# Links

!SLIDE 
# This presentation #
## atomicobject.github.com/source\_control

!SLIDE smaller
# SVN
* [svn book](http://svnbook.red-bean.com/en/1.6/svn-book.html)
* [svn Quick Reference Card](http://www.collab.net/community/subversion/articles/SvnQuickReferenceCard.html)

!SLIDE
# Git
* [gitready](http://gitready.com)
* [gitref](http://gitref.org)

!SLIDE
# Tools we used to build this preso: #
* github.com/shacon/showoff
* checkvist.com
* google.com/webfonts

!SLIDE incremental bullets
# Thanks!
* (btw, Atomic runs a cool summer internship program)
* atomicobject.com/jobs
