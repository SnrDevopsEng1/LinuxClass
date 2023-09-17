Intro to class orientation, q and a

**week1 day2


Intro to computer basics hardwares and software 

** Linux commands

**cli ==> command line interface
Linux Flavors: centos, ubuntu Debian

date    ==> to check the date on the server
uptime  ==> to check how long the system have been running
clear   ==> the clear the terminal screen
free -m ==> check the total memory used and available memory
pwd     ==> print working directory ( check where you are on the server)
mkdir   ==> create folders or directories on the system
ls      ==> list directory content
touch   ==> create files 
history ==> check all previous typed commands
man     ==> manual of a command.
lsblk  ==> list block device ( hard drives)

%%%%%%%%%%%%%%%%%%%%%%%%%%%%  week2 %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

day 1 : intro to linux
  created in 91 by Linus Torvalds
  different flavor :
    centos
    ubuntu
    debian
    kali
    mint
    alpine
    redhat
    fedora 
    and more ....
  linux components:
    Linux is composed of several key components that work together to provide the functionality of the operating system. 
These components include:
Kernel: The Linux kernel is the core of the operating system. It manages hardware resources, controls system processes, 
and provides services to applications.
Shell: The Linux shell is a command-line interface that allows users to interact with the operating system. 
It is a powerful tool that can be used to perform a wide range of tasks, from basic file management to complex system administration.
Filesystem: The Linux filesystem is a hierarchical structure that organizes files and directories. It is based on the Unix filesystem and provides a standardized way of accessing and storing data.
Applications: Linux supports a wide range of applications, including web browsers, office suites, media players, and development tools. Many applications are open source and can be freely downloaded and modified.
Libraries: Linux includes a large collection of libraries that provide common functionality to applications. These libraries can be used by developers to simplify the development process and make their applications more efficient.
Utilities: Linux includes a variety of utilities that provide additional functionality, such as text editors, network tools, and system monitoring tools. These utilities are often command-line based and can be used to automate tasks or perform complex operations.

Linux commands:
  
date    ==> to check the date on the server
cal     ==> to check the calendar
uptime  ==> to check how long the system have been running
clear   ==> the clear the terminal screen
free -m ==> check the total memory used and available memory
pwd     ==> print working directory ( check where you are on the server)
mkdir   ==> create folders or directories on the system
ls      ==> list directory content
touch   ==> create files 
history ==> check all previous typed commands
man     ==> manual of a command. 
nproc   ==> check number of cpu
lsblk  ==> to check block device or hard drive
lscpu  ==> check cpu info 


Day 2 :
  Linux command practice:
    

    
*** System inventory ( server decommisioning , Server end of lease, end of life. )

	uptime ==> to check how long the system have been running
    lscpu ==> check cpu info
    cat /etc/os-release  ==> os type and version
    nproc  ==> check number of cpu
    lsblk  ==> to check block device or hard drive
    uname -r ==> to check the kernel version
    top   ==> to check cpu, memory, uptime, and all the process running   
    free -m  ==> to check memory
    
*** files/directories commands
  	 mkdir  ==> to create folders
     touch  ==> to create files
     ll, ls, ls -l  ==> to list directory content
     cd  ==> to change directory
     cp, cp -r  ==> to copy files and directory 
     mv  ==> to rename a file or move it to a new location
     find ==> use to check file or directory path
     vi  ==> to edit files
     cat ==> display file content
     rm, rm -f ==> to delete files and directories
     rm -r, rm -rf  ==> to delete files and directories
    
*** Other commands:
    man
    history
    echo
  
Project1:
  1- You receive a request to create a test centos 7 server. go ahead and create it with lightsail service.
  with below specs:
   region: n. Virginia
    platform: linux
    blueprint: os only
    os :  centos 7
    keypair: N/A
    cpu: 1
    Memory: 512 MB
    Server Name: dev-test-server
      
  2- what is linux ?
  3- what are the features of linux 
  4- what is the linux architechture or  the components of linux?
  5- what is cli ?
  6- what is a shell?
  7- login remotely to the server created in question1 and do a complete inventory
  8- create a file called linux_command
  9- add 30 linux command in the file linux_command and what they are for.
  10- what is your favorite command in linux and why?
 11- what are some linux flavor that you know ?
 12- delete the centos 7 server created in question 1.
 
%%%%%%%%%%%%%%%%%%%%%%% week 3 %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

chtGPT link 
https://chat.openai.com/chat

**Linux commands review

        1 date ==> to check the date
        2 uptime ==> to check how long the server have been up
        3 whoami ==> to check who is logged in
        4 cd ==> to change directory
        5 cp ==> to copy files and directory
        6 mv ==> to rename a file or move it to a new location
        7 free ==> to check memory
        8 touch ==> to create files
        9 clear ==> to clear the terminal
       10 top ==> to check cpu, memory, uptime, and all the process running
       11 uname -r ==> to check the kernel version
       12 history ==> to check previous typed command
       13 exit ==> to exit a terminal or a user
       14 echo ==> to display any message
       15 sudo ==> to escalate privilege
       16 mkdir ==> to create folders
       17 lsblk ==> to check block device or hard drive
       18 cal ==> to check the calendar
       19 man ==> to check documentation about specific command
       20 ls ==> to list directory content
       21 pwd ==> to check the current working directory
       22 rm ==> to delete files and directories
       23 nproc ==> check number of cpu
       24 ssh ==> use to login to a linux server remotely 
       25 find ==> use to check file or directory path
       26 vi ==> to edit files
       27 id ==> to check user's id
       28 df ==> to check disk utilisation
       29 lscpu ==> check cpu info 
       30 cat ==> display file content
       31 more ==> display one page document at the time
       32 less ==> display one page document at the time
       33 grep ==> filter strings from file
       34 wget ==> download file from a url source
       35 yum, apt, ==> install packages 
       36 ping ==> check connectivity between two devices.
       37 systemctl ==> start, stop, restart, enable 
       36 cat /etc/os-release ==> os type and version 
 
