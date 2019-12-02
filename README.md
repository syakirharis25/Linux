My works related to Linux operating system.

## Table of Contents
1. [Introduction.](#introduction)
2. [Official websites.](#websites)
2. [GitHub notes.](#github)

<a name="introduction"></a>
## Introduction
<img src="Linux-Foundation.jpg" height="150">
Linux is the largest and most pervasive open source software project in history. It has seen massive acceptance in almost every sector, including financial services, government, education, and even film production. Linux is also the operating system of choice to support cutting-edge technologies such as the Internet of Things, cloud computing, and big data.

The Linux Foundation and its projects have more than 1,000 corporate members across the Americas, Asia-Pacific, and EMEA, including companies that are leaders in the strategic use of open source. A few include AT&T, Cisco, Fujitsu, Hitachi, Huawei, IBM, Intel, Microsoft, NEC, Oracle, Qualcomm, and Samsung.

Linux began in 1991 as a personal project of Linus Torvalds while studying computer science at University of Helsinki to create a new free operating system kernel. The resulting Linux kernel has been marked by constant growth throughout its history. Since the initial release of its source code in 1991, it has grown from a small number of C files under a license prohibiting commercial distribution to the 4.15 version in 2018 with more than 23.3 million lines of source code, not counting comments, under the GNU General Public License v2.

A Linux distribution (often abbreviated as distro) is an operating system made from a software collection, which is based upon the Linux kernel and, often, a package management system. Linux users usually obtain their operating system by downloading one of the Linux distributions, which are available for a wide variety of systems ranging from embedded devices and personal computers  to powerful supercomputers.

<a name="github"></a>
## Official websites
The Linux Foundation official website : https://www.linuxfoundation.org

**_Linux Distros_** <br />
Ubuntu official website : https://ubuntu.com <br />
Debian official website : https://www.debian.org <br />
Kali official website : https://www.kali.org <br />
Parrot official website : https://parrotlinux.org/ <br />

Oracle VM VirtualBox official website : https://www.virtualbox.org

Linux operating system was created by Linux Torvalds : https://github.com/torvalds

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
