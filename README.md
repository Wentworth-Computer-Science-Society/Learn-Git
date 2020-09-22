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

```ls```:lists all files and directories that are direct children of the current directory 

```cd <directory>```:This command navigates you around the command line.
####


## Git commands

Git has a range of commands, here we are going to try to cover the essential commands and when you would commonly use each one

```git init```: Creates a git repository in the current directory<br/>
```git clone <repository-url>```: Downloads a remote git repository into the current directory</br>
```git status```: Shows information about the git repository and files that are modified or staged<br/>
```git commit -m "Message"```: Creates a new git commit<br/>
```git add <file>```: Adds files to staging<br/>
```git branch```: shows branches<br/>
```git branch <branch-name>```: Creates new branch<br/>
```git checkout <branch-name>```: Switch to branch<br/>
```git merge <branch-name>```: Merges branch into current branch<br/>
```git rebase <branch-name>```: Moves branch onto a new base<br/>
```git stash```: Moves changes from working-directory<br/>
```git stash pop```: Re-applies previously stashed changes<br/>

## Resources for learning git

These resources should be a great start and get you to understand the essentials of git. It is important to remember that the fastest way to learn is to try things yourself. I would reccomend creating a github account if you do not have one and start writing code in a git repository. This way, you can track changes over time, as well as have a nice portfolio for employers to look at! In addition, you will certainly run into scenarios that will cause you to learn more about git.

[MIT Lecture on Version Control](https://www.youtube.com/watch?time_continue=5&v=2sjqTHE0zok&feature=emb_logo)<br>
[Interactive Git Branching Tutorial](https://learngitbranching.js.org/)<br>
[Linkedin Learning Course on Git](https://www.linkedin.com/learning/git-essential-training-the-basics/use-git-version-control-software-to-manage-project-code?u=2212297)<br>


## Exercises

### Exercise 1: Local Git

a. Create an empty directory<br>
b. Initialize it as a git repository<br>
c. Create a file called Learn-Git.txt<br>
d. Open the file with a text editor and write some text into the first line of the file<br>
e  Stage your changes<br>
f. Commit the changes you made to the master branch<br>
g. Create a new branch called feature1<br>
h. Create a new branch called feature2<br>
i. Switch to the feature1 branch that you just created<br>
j. Delete the text in Learn-Git.txt and replace it with a different string of text<br>
k. Stage your changes and commit them to the local branch<br>
l. Switch to the master branch<br>
m. Merge your changes from feature1's branch (there will be a merge conflict you need to resolve)<br>
n. Switch to the feature2 branch<br>
o. Open Learn-Git.txt and add some text on line 2<br>
p. Stage and commit your changes<br>
q. Rebase your changes on master<br>
r. Switch to the master branch<br>
s. Merge feature2 into master. There should be no conflicts, ask yourself why not?<br>

### Exercise 2: Working with a remote repository

a. Clone this repository following [this link](https://github.com/Wentworth-Computer-Science-Society/Learn-Git)<br>
b. Create a new branch named as FirstName-LastName<br>
c. Open People.md<br>
d. Add your name to the file on a new line<br>
e. Stage your changes<br>
f. Commit your changes and push the branch to the remote repository<br>
g. Go to [the repository url](https://github.com/Wentworth-Computer-Science-Society/Learn-Git) and create a pull request to merge your changes into the master branch<br>
h. Check back and you will see when the changes are merged in :)<br>
