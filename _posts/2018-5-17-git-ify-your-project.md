---
layout: post
title: git -ify your project!
---

Hey flocks, today we will be nurturing git.

* ***What is git?***

git is a VCS (i.e. version control system) to maintain project source codes in an awesome manner.

* ***What is the feature of git?***

1. we can go back to the previous version of the code.

1. multiple members from the same project can easily share and save their codebase easily.

1. we can retrieve our code from anywhere anytime.

1. project with multiple team member can easily sync their code.

1. git is a distributed architecture.

1. we can easily implement the local › staging/sandbox › production workflow for codebase by git.

1. there are many!

* ***how to use git?***

![](https://cdn-images-1.medium.com/max/2000/0*OBLMPw7vugF2YJUs.png)

so we can use different branches to execute this workflow.

* ***Important git commands***

1. First, we need to go to the project root directory and then initialise git with ***git init. N***ow git has been initialised into our project and ready to start.

1. we need to choose some repo hub like Github, bitbucket,gitlab etc. to use as a server for git. Here our source code will reside. We need to first create an a/c in any of this hub for git. Then we need to create a repository suppose to say in github.com.We will get a remote URL with two types(i.e. in ssh URL and another is https based.).we will choose ssh URL and for this we need to create an ssh key in our machine and add the public key to the hub, like Github a/c. If we need help on creating ssh keys please follow **http://bongweb.com/using-multiple-ssh-keys/.**

1. we need to attach our directory to the remote repo with ***git remote add origin ‘remote-url’. ***now we can insert (i.e push) to that repo URL.here origin is a pointer to that remote URL.

1. now need to add files in git, so that git can track changes. The command is ***git add . ***or*** git add -A to ***add all files in directory.

1. now changes are tracked by git but not saved. to save our changes we need to use commit i.e. ***git commit -m “message”.***

1. to check the status of git tracking we use ***git status.***

1. now our code is ready to push(i.e insert) to remote git repo url.we can use ***git push origin master.master is by default branch created. ***it’s the main branch.

1. we can check all commits of the project having git with ***git log***.

1. we can get our full code by ***git clone ‘remote-url’.***

1. after cloning the source code if the new code is pushed, if we need updated code we can pull our recent commits by ***git pull origin master.***

1. we can check the current branch with ***git branch.***

1. we can create a new branch with ***git branch ‘branch-name’ or git checkout -b ‘branch-name’.***

1. we can delete a branch with ***git branch -D ‘branch-name’***

1. we can switch between branches by ***git checkout ‘branch-name’***

1. we can check connected remote URLs using ***git remote -v.***

1. we can change remote URL pointed with origin by ***git remote set-url origin ‘new-url’.***

these are all basic kinds of stuff with git.we can follow the above image’s development workflow with git’s different branches as the master for production, stage for staging, local for local development. git -ify your project!
