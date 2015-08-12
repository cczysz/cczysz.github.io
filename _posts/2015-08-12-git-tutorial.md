---
layout: post
title: Git Tutorial
---

# Git versus Github

Git is a versioning software, similar to SVN, Mercurial, and others. It can be used locally, storing changes in a .git directory. It can also be used to store repositories online, such as on Github or Bitbucket.

# Using git on Tarbell

Git should already be installed for you on tarbell. Confirm this by typing `git`.

The `git` command is a quick way to see all available subcommands. The most important commands for us are:

* `git add`
* `git commit`
* `git push`

# Init

Before using git, there are a few defaults you'll want to set.

`git config --global user.name "<name>"`

`git config --global user.email "<email>"`

To set up a repository, make a new directory, `cd` into it, and run `git init`

To download an existing repository

`git clone <url>`

