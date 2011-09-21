!SLIDE
<link href='http://fonts.googleapis.com/css?family=Comfortaa:400,700' rel='stylesheet' type='text/css'>
# What is Source Control #

!SLIDE bullets incremental
# Our definition: #

* "Process and tools that let you obtain the latest code for your project, then 
merge and store your updates in the code repository"

!SLIDE bullets
# Other definitions: #

* "Revision control"
* "Version control"
* "Software configuration management"

!SLIDE
# Stuffy terms, wrong focus #

!SLIDE bullets incremental
* "The management of changes to documents, programs, and other information stored as computer files."
* *yawn*


!SLIDE commandline incremental
$ svn checkout

!SLIDE commandline incremental
$ svn diff

!SLIDE commandline incremental
$ svn log

!SLIDE commandline incremental
$ svn checkin


!SLIDE center
![Subversion, Git, Mercurial, Darcs, CVS](sc_logos.png)

!SLIDE incremental bullets
    svn co [output]
    svn diff [output]
    svn log [output]
    svn ci [output]

!SLIDE
# Check This Code #
    @@@ Ruby
    code_here()

!SLIDE 
# SVN: A day in the life #

!SLIDE 
# svn up #

!SLIDE 
# (edit code) #

!SLIDE 
# svn diff #

!SLIDE 
# svn up (again) #

!SLIDE 
# svn checkin -m#

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
* Checkin

!SLIDE
# LINKS! #
* http://atomicobject.github.com/source\_control

!SLIDE
# SVN Command ref / tutorials #

!SLIDE
# Git ref / tutorials #

!SLIDE
# Tools we used to build this preso: #
* http://github.com/shacon/showoff
* http://checkvist.com
* (Google web fonts)


