My works related to Linux operating system.

## Table of Contents
1. [Introduction.](#introduction)
2. [GitHub notes.](#github)

<a name="introduction"></a>
## Introduction
<img src="Linux-Foundation.jpg" height="150">

<a name="github"></a>
## GitHub notes
Initialize repository, adding GitHub remote repository and check the remote repository
```
$ git init
$ git remote add origin https://github.com/syakirharis25/Linux.git
$ git remote -v
$ git status
```
If there is a message <br />
Please move or remove them before you merge. <br />
Aborting

Then do this commands.
```
$ git clean -d -f
$ git pull origin master
$ git status
```
