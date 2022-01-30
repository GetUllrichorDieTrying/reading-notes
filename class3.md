# Code Fellows 102

## Class 3: Git-GitHub

### Git Intro

- Git is a Distributed Version Control System (DVCS).
  - A DVCS allows for multiple mirrored repositories, which enables easy team collaboration.
  - Git takes snapshots of your data, works locally, tracks changes, and prevents the loss of data.
- Git can reside in 3 states
  - Committed: Stored in local database.
  - Modified: File has been changed but not committed to the database.
  - Staged: Flagged a file's version to be committed in next snapshot.

### ACP

  (A)DD
  (C)OMMIT
  (P)USH

### Git Commands

Set user name and email for Git

`git config --global user.name "Jane Smith"`

`git config --global user.email "example@email.com"`

Confirm user name and email for Git

`git config --global user.name (should return Jane Smith)`

`git config --global user.email (should return example@email.com)`

Check Settings

`git config --list`

#### Import Git Repository

1. Switch to target project directory

  `cd targetdirectory`
2. Use git init command

  `git init`
3. Start tracking files by preforming initial commit

  `git add *.c`
  `git add LICENSE`
  `git commit -m “any message here”`

#### Clone Git Repository

`git clone https://github.com/test`

Clone and put in named directory

`$ git clone https://github.com/test nameddirectory`

#### Check File Status

`git status`

#### Tracking and Staging New File

Single File

`git add filename`

All Files

`git add *`

#### Committing a File

`git commit -m “made change x,y,z”`

#### Comitting All Changes

`git commit -a`

#### Pushing Changes

`git push origin master`

### Git Workflow

#### Local Repo Structure

1. Working Directory: files reside here
2. Index: the area for staging changes
3. Head: Points to most recent commit

#### Saving Changes

Tracked: Part of most recent snapshot

Untracked: Not in the last snapshot and not currently in the staging area.

[HOME PAGE](https://getullrichordietrying.github.io/reading-notes/)
