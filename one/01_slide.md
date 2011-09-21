!SLIDE
<link href='http://fonts.googleapis.com/css?family=Comfortaa:400,700' rel='stylesheet' type='text/css'>
# What is Source Control #

!SLIDE bullets
# Other definitions: #

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

* "Process and tools that let you obtain the latest code for your project, then 
merge and store your updates in the code repository"

!SLIDE center
# Choices
![Subversion, Git, Mercurial, Darcs](sc_logos.png)

!SLIDE
# Subversion Samples 

!SLIDE
# svn checkout #

!SLIDE commandline incremental
<pre style="font-size: 24pt">
$ svn checkout https://svnserver/sample_proj

A    sample_proj/README.txt
A    sample_proj/Hello.java
</pre>

!SLIDE
# svn log #

!SLIDE
<pre style="font-size: 16pt">
$ svn log

------------------------------------------------------------------------
r1598 | crosby | 2011-09-20 20:27:47 -0400 (Tue, 20 Sep 2011) | 1 line

Sketched Hello.java
------------------------------------------------------------------------
r1597 | crosby | 2011-09-20 19:55:48 -0400 (Tue, 20 Sep 2011) | 1 line

Starting SVN sample for Everyday Source Control
------------------------------------------------------------------------
</pre>

!SLIDE
# svn commit #

!SLIDE 
<pre style="font-size: 16pt">
$ svn ci -m "Added CHANGELOG area to README.txt"

Sending        README.txt
Transmitting file data .
Committed revision 1599.
</pre>


!SLIDE incremental
# Significance in software development
* Pervasive, intrinsic
* Ubiquitous but varied

!SLIDE bullets incremental
# Code goes in SC.
* *Always.*

!SLIDE
# Why?
* track and document
* protect / recover
* work with others
* find in future

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


