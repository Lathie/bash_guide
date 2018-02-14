# Bash Guide

## Basics

### What is a Shell

According to Wikipedia: A shell is a user interface for access to an operating system's services.

### What is Bash

Bash is a command line (CLI) unix shell. It stands for the **B**ourne **a**gain **sh**ell.

### What shell should you use?

There are many shells out there, from the Bourne shell (sh), to more modern shells like zsh and fish. I personally recommend Zsh.

## Setup

### Linux 

Open up your favorite terminal emulator :) 

### MacOS

Open up your Terminal. 

For better features and a more powerful terminal, install [iTerm2.](https://www.iterm2.com/)

You will also want [Homebrew](https://brew.sh/) for package management.

### Windows

You could use [bash for Windows 10](https://docs.microsoft.com/en-us/windows/wsl/install-win10).

Developing on a Windows computer is needlessly complicated, so I would recommend either dualbooting or running some flavor of Linux in a VM. 
VMWare is free for UIUC students on the webstore and VirtualBox is free.

## Using Bash 
### Basic Navigation

`ls` - List Directory Contents

`cd <dir>` - Change Directory

`pwd` - Print Working Directory

### Interacting with your filesystem

`mkdir <dir>` - Make a directory

`touch <file>` - Make a file

`nano` - Basic text editor

`cat <file>` - "Concatenates" files to standard output (the terminal output)

`cp <file> <dest>` - Copy a file

`mv <file> <dest>` - Move a file

`rm <file>` - Remove a file

`man <command>` - Information about commands

### Flags

Commands will often let you specify flags, or additional options to them in the format `-<char>`. 

Here are some interesting flags that may be useful:

`ls -a` - List all (including hidden files)

`ls -l` - List files in long form

`ls -la` - List all files in long form

`rm -r` - Remove recursively

`sl -alFc` - ?????

## Programming

### Package Management

With the command line, there must be a way of installing new programs. This is where package management comes in. 
Package management programs allow you to install and delete programs. These programs vary depending on what type of system you have.

Debian based Linux - Apt

MacOS - Brew

### Python

You can install python from your package manager. Be careful you install the correct version as there are differences between python 2 and python 3

`python <pythonfile.py>` - Run a python program

`python --version` - Check your python version

### Java

You can install java from your package manager. Just like python there are many different java versions so be careful.

`javac <javafile>` - Compile a Java program

`java <javaprogram>` - Run your java program

## Advanced stuff

### Piping

You can redirect a program's standard out into another program's standard in with the pipe character.

`fortune | cowsay` - ?????



