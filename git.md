# Intro to Git

## What is git?

Git is a distributed version control. It allows you to work on code with others while keeping your code on you personal machine.

What does git let us do?
  - Revert our code to a workable state in case we break it. (version control)
  - Work on code with others by sharing one repository.
  - Share our code with others who might benefit from it.

How to get started with git:
  - install git
  - create a free github account
  - create your first repository on github.com
  - clone this repository to your computer 

If you decide you like git I recommend setting up ssh so that you don't have to login everytime you want to push or pull code.

## Git terminology

  - repositories (AKA repo) - A collection of all the files and history of those files 
    - remote repository - the repository on github or a similiar service
    - local repository - the repository on your machine
  - commit - the act of creating a snapshot of your code
  - cloning - the act of copying a repository from a remote server to your device
  - branch - A bunch of commits linked together, you can have branches stem off of another branch
  - HEAD - A reference to the most recent commit
  - main - This was previously known as master, it is the main branch in your project
  - branching - to create a branch off of another branch
  - merging - to merge two branches together

## Git actions

  - status - tells you what files have been modified and what files are on the staged
  - add [file(s)] - this adds the files you select to your staging index to be commited into the snapshot
  - commit - this takes a snapshot of whatever files are on the loading stage
  - push - this pushes all snapshots since the last push to your remote repository
  - pull - this pulls all snapshots that your repository doesn't have to your machine
  - branch - allows you to see and create branches
  - log - shows you the history of your commits
  - checkout - allows you move between branches **and** snapshots/commits
  - init - initializes a git repo on your computer
  - clone - clones a repo onto your device
  - diff - show unstaged changes you have made
  - merge - merge one branches commits into another branches

## Want to learn more?

  - interactive git tutorial https://learngitbranching.js.org/
  - shell tutor, created by our own Erik Falor and Jaxton Winder, module 6 is all about git - https://gitlab.cs.usu.edu/erik.falor/shell-tutor 
