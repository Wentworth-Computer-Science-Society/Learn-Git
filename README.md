# Learning Git

## Introduction

Version Control Systems help developers track changes made to a codebase over time. Having a history of your project can help you to revert changes, version your releases and identify where bugs may have appeared. In addition to having a historical view of your project, you also gain the ability to collaborate with others. This is where the power of git really begins to shine. Developers can work in parallel in the same codebase to develop features and can merge those changes together using version control software. Git is the most popular version control system and is widely adopted by many companies across the world. In fact, this file that you are currently reading is a git repository itself, hosted on GitHub, a website for hosting git repositories in the cloud. 

In this tutorial, we will be covering what git is, how you can use git to collaborate with others, and then go into some common scenarios where git help save you time. At the end, we have some exercises for you to work through.

## Getting started Instructions
To begin with, we need to install git onto our local machines
## Windows
Follow [this link](https://git-scm.com/download/win) to download git for windows

I would highly reccomend using the git bash terminal which comes with your installation of git on your windows machine. Using command prompt for this tutorial may give some slight issues as the commands are slightly different than a bash terminal. Bash commands are extremely useful to learn and will be used most often as a software developer, so again I will advise using the bash terminal.
## Mac
Open up the terminal and enter the following:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
brew doctor
```

You will be offered to install command lines tools for Mac, confirm this by clicking install

Once this is complete, you can now install git with the following command:

```
brew install git
```

## The command line

Git can be very confusing to learn at first, the most common problem with learning git is that the interface is not very user-friendly for beginners. While the command line is a great concise tool, new users that aren't familiar with how the to navigate the command line might struggle.
### File System Structure
The first thing you need to better understand both the command line, and git, is the structure of files in a computer

There are two primary commands that can be used to navigate the file structure of a git repository
```
ls : lists all files and directories that are direct children of the current directory 
```
```
cd <directory> : Navigates you to the directory you pass to the command as an argument. This is relative to where you currently exist in the file system.
```
####


## Git commands

Git has a range of commands, here we are going to try to cover the essential commands and when you would commonly use each one

## Exercises
