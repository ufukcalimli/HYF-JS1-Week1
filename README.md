# HYF GIT

Hack Your Future Git classwork.

## Version Control

Version control systems are a category of software tools that help a software team manage changes to project's source code over time. 

## Why Version Control?

1. History
    - Keep a track of every change we make to our project. We can know which code was added on which day to which particular file. Thus, if a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the bug while minimizing disruption to all team members.
2. Collaboration
    - Allows multiple developers to work on the same project with ease without having to worry about to manage changes from all of them. Without a VCS, a developer has to get a lock on a file he/she is editing so that no one else touches that file and hence avoid the painful task of merging all changes manually.

## What is Git?

Git is one of the most popular version management tools available. In addition to common VCS features, one of the advantageous feature that Git provides is its branching capabilities. In Git, each developer gets their own local repository, complete with a full history of commits. This allows all developers to work in an isolated environment using feature branches.

## Create a Git repository

`git init` - creates an empty git repository. An initial HEAD file that references the HEAD of the master branch is also created.

`git clone` - create a copy of an existing repository on your machine. Internally, it calls `git init` to create a repository and later copies contents from the repository to your machine.

## Git staging

Files in a repository go through three stages before being under version control with Git. Use `git status` to understand which stage the files in repository are at.

1. Untracked
    - The file exists but is not part of Git's version control. Use `git add` to add files to staging area.
2. Staged
    - The files here are in the staging area and ready to be committed.
3. Committed
    - Use `git commit` to create a record or a snapshot of changes which you have made. Usually, this is done by recording a short message that explains what we did and why.
    - One useful command in this section is `git commit --amend` flag, which allows you to amend the previous commit, for example to fix a spelling mistake.
