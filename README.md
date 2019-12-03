My works related to Linux operating system.

## Table of Contents
1. [Introduction.](#introduction)
2. [Official websites.](#websites)
3. [Oracle VM VirtualBox display configuration.](#virtualbox)
4. [Bash script.](#bash)
5. [GitHub notes.](#github)

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

<a name="virtualbox"></a>
## Oracle VM VirtualBox display configuration
Oracle VM VirtualBox (formerly Sun VirtualBox, Sun xVM VirtualBox and Innotek VirtualBox) is a free and open-source hosted hypervisor for x86 virtualization, developed by Oracle Corporation. Created by Innotek GmbH, it was acquired by Sun Microsystems in 2008, which was, in turn, acquired by Oracle in 2010.

VirtualBox is free and open source virtualization software from Oracle. It enables you to install other operating systems like Linux operating system in virtual machines. It is recommended that your system should have at least 4GB of RAM to get decent performance from the virtual operating system.

By default the default graphic controller setting in Oracle VM VirtualBox is set to VMSVGA, this caused the system to operate very slow especially if you are using Microsoft Windows 10. To fix this press **[Ctrl]** + **[S]** on your keyboard, then click on the Display on the right of the VirtualBox user interface, and then under the Graphics Controller drop down list, select **[VBoxVGA]** and start the Linux virtual machine to check back the performance of the machine.

<a name="bash"></a>
## Bash script
In the realm of Linux (and computers in general) we have the concept of programs and processes. A program is a blob of binary data consisting of a series of instructions for the CPU and possibly other resources (images, sound files and such) organised into a package and typically stored on your hard disk. When we say we are running a program we are not really running the program but a copy of it which is called a process. What we do is copy those instructions and resources from the hard disk into working memory (or RAM). We also allocate a bit of space in RAM for the process to store variables (to hold temporary working data) and a few flags to allow the operating system (OS) to manage and track the process during it's execution.

Essentially a process is a running instance of a program. When we are at the terminal we have a Bash process running in order to give us the Bash shell. If we start a script running it doesn't actually run in that process but instead starts a new process to run inside.A Bash script is a plain text file which contains a series of commands.

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
