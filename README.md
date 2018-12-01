# HYF GIT

Hack Your Future Git classwork.

## Version Control

Version control systems are a category of software tools that help a software team manage changes to project's source code over time. 

### Why Version Control?

1. History
    - Keep a track of every change we make to our project. We can know which code was added on which day to which particular file. Thus, if a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the bug while minimizing disruption to all team members.
2. Collaboration
    - Allows multiple developers to work on the same project with ease without having to worry about to manage changes from all of them. Without a VCS, a developer has to get a lock on a file he/she is editing so that no one else touches that file and hence avoid the painful task of merging all changes manually.

### What is Git?

Git is one of the most popular version management tools available. In addition to common VCS features, one of the advantageous feature that Git provides is its branching capabilities. In Git, each developer gets their own local repository, complete with a full history of commits. This allows all developers to work in an isolated environment using feature branches.

## Installation ##

#### Install project dependencies ####

```bash
npm install -g gulp

npm install
```

## Local dev server ##

#### Run dev server for Style Guide application ####

```bash
gulp
```

Server will be running at: `http://localhost:8080/`


#### Run code checks ####

```bash
gulp lint
```

## Release build ##

#### Creates artificats for deployment purposes ####

```bash
gulp release
```

Output: `./_build/prod`