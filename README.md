
---
title: Intro to Git
date: September 2018
...

## Version Control Systems (Git)

Version control allows a software team to simultaneously modify the same files and keep track of thousands of different versions of their code. 

Each version is created with a "commit." A commit consists of:

1. The difference between the new version and the old version.
2. The date and time the new version was created.
3. The name of the author (who wrote the changes in the new version).
4. The name of the committer (who added the changes to the project).

---

## Version Control Systems (Git)

All software projects can be broken down into a series of commits.

Git is the name of the version control system (VCS) that has been the most popular in the last decades. 

Companies (such as Github, Bitbucket, Gitlab, etc.) have built platforms to help teams work with Git. 

---

## Forking

Permission is needed to add a commit to a project on a public repository. 

In open source projects, this permission is not given to everyone, it is instead held by a core team. 

"Forking" is the act of copying all the commits (and therefore all the code) from a public repository into a new one that you own. This allows anyone to create new commits, modifying their own fork of the project.

---

## Merging

After forking a project and adding a new commit, outside authors can send that new commit back to the project owners to be "merged" back into the original repository. 

One primary role of the platforms is to facilitate this process, along with all the necessary communication between the outside author and the core team. 

On Github, this is called "opening a pull request"

---

## Cloning

Git consists of two parts: client and server. 

When using a hosted platform, such as Github, the server is hosted by them!

The client is run by you on your development machine. 

The act of "copying" a repository of code onto your machine is called "cloning"

---

## Cloning

When you clone a project, you copy all of the commits in the entire project onto your local machine:

```{sh}
git clone https://github.com/bgsedatascience/module-git
```

---

## Committing


---

## Pushing


---


