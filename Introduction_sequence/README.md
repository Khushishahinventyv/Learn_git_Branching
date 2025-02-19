# Introduction to Git

Welcome to the Git Introduction Sequence! This guide will walk you through the fundamental concepts of Git, including committing, branching, merging, and rebasing.

---

## Level 1: Introduction to Git Commits
A commit in a Git repository records a snapshot of all the tracked files in your directory. Think of it as a "save point" in your project's history.

### Commands
```bash
$ git commit
$ git commit
```

### Result
![alt text](image-9.png)
---

## Level 2: Branching in Git
Branches in Git are lightweight pointers to specific commits. This makes working on multiple features or bug fixes seamless and efficient.

> **Best Practice**: *Branch early, and branch often!*

### Commands
```bash
$ git branch bugFix
$ git checkout bugFix
```

### Result
![alt text](image.png)
---

## Level 3: Merging in Gits
Now that we can commit and branch, it's time to learn how to combine changes from different branches. Merging allows us to develop features separately and then integrate them back into the main branch.

### Commands
```bash
$ git branch bugFix
$ git checkout bugFix
$ git commit
$ git checkout main
$ git commit
$ git merge bugFix
```

### Result
![alt text](image-1.png)

---

## Level 4: Rebasing introduction
Rebasing replays commits from one branch onto another, creating a cleaner and more linear commit history.


### Commands
```bash
$ git branch bugFix
$ git commit
$ git checkout bugFix
$ git commit
$ git checkout main
$ git rebase bugFix
$ git branch -f main c3
$ git branch -f bugFix c2'
$ git checkout bugFix
```

### Result
![alt text](image-2.png)


