# Basic Git Commands

Here’s a guide to the most essential Git commands, categorized for convenience.

## 1. Setting up Git

Before you can start using Git, configure your identity so that it’s tied to your commits. This only needs to be done once per machine.

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

```

## 2. Starting a Repository

a. Initialize a Git Repository

To start tracking changes in a project, you need to initialize Git in the project directory.

```bash
git init

```

This creates a .git folder where Git stores the history of changes.

b. Cloning a Repository
Cloning copies an existing Git repository from a remote server to your local machine.

```bash
git clone <repo-url>
```
This will download all files and the entire history of the project.


## 3. Tracking Changes

a. Check the Status
You can see which files have changed, which files are staged for the next commit, and which files are untracked using:

```bash 
git status

```

b. Stage Files
To add changes to the staging area (files you want to include in the next commit):

```bash
git add <filename>

```
Or to add all changes:

```bash

git add .

```

c. Commit Changes
Once files are staged, you create a commit to record your changes with a meaningful message:

```bash

git commit -m "Descriptive message of the changes"
```

## 4. Viewing Commit History
View the history of commits to your project:

```bash

git log

```