---
title: A Fresh Start With Git
date: 2024-10-02 22:11:00 +0700
categories: [Tech]
tags: [git]
image: /assets/img/A-Fresh-Start-With-Git/git.png
---

About 2 weeks ago, the lecturer of CSC14003 (Introduction to AI) gave us a choice to learn courses from Udemy, Coursera, or any other online learning platform to get that juicy extra credit *chef kiss*. Coincidentally, I have a Git course from Udemy that I got for free a while back, and Git is something that I've been wanting to learn more about. Killing two birds with one stone type of situation, I guess. Ofc, a proof of some sort is required to get the credit and writing a blog post is one of the options. So here I am, writing this blog post to get that extra credit. Without further ado, let's get started.

## What is Git?
Git is a distributed version control system that is used to track changes in source code during software development. It is designed to handle everything from small to very large projects with speed and efficiency.


# Section 2: Git Basics: First steps
## File states in Git
![alt text](/assets/img/A-Fresh-Start-With-Git/git-lifecycle.png)

There are 3 states that a tracked file can be in Git:
1. **Staged**: The file has been marked for inclusion in the next commit.
2. **Committed**: The file which were staged have been committed to the Git repository.
3. **Modified**: The file has been modified since the last commit but has not been staged.

## Git commands
- `git init`: Initialize a new Git repository.
- `git add <filename>`: Add a file to the staging area.
- `git commit -m \<message\>`: Commit changes to the repository.
- `git status`: Show the working tree status.
- `git log`: Show the commit logs.
- `git rm --cached \<filename\>`: Remove a file from the staging area but keep it in the working directory.
- `git commit --amend`: Modify the last commit (potentially dangerous if the commit has been pushed to a remote repository).

## What is gitignore?
`.gitignore` file is used to specify files and directories that should be ignored by Git. It is useful when you have files that you don't want to commit to the repository.



