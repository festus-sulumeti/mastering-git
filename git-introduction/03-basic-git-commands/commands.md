# Basic Git Commands

Here’s a guide to the most essential Git commands, categorized for convenience.

Note that this is a beginner's guide. Incase some of the concepts commands are found to be difficult, do not worry there are other folders within the repository that are going to state deeply on what the commands witnessed in this place are, and the role they play 

## 1. Setting up Git

Before you can start using Git, configure your identity so that it’s tied to your commits. This only needs to be done once per machine.

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

```

## 2. Starting a Repository

a. Initialize a Git Repository

To start tracking changes in a project, you need to initialize Git in the project directory.
create a folder with which you will initialize it with

```bash
git init

```

This creates a .git file within the folder where Git stores the history of changes.

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

This will display the commit history, including commit IDs, messages, and authors.

## 5. Branching and Merging
At this stage, we have a small introduction on branching and merging. 
More details on what it is will be covered in other well stated folders inside the repository.

The key point to be taken at this stage is that with braching and merging, it mainly occurs when you  want to work in team with other developers or maybe you might want to work alone but have the need that you prefer not to temper with the original file that is in the main repository while you are creating your project 

The following is a surface basics on how to go about it 

a. Create a New Branch
To start working on a new feature or bug fix, create a new branch:

```bash

git branch <branch-name>

```
b. Switch to the Branch
Move to the branch you created:

```bash

git checkout <branch-name>

```
c. Merging Branches
When the feature is ready, merge it into the main branch:

```bash

git merge <branch-name>
```
## 6. Working with Remotes

a. Adding a Remote Repository
If you have a project hosted on GitHub, you can link it as a remote:

```bash
git remote add origin <remote-url>
```
b. Pushing Changes
After making commits, push them to the remote repository so others can access your work:

```bash
git push origin <branch-name>
```
c. Pulling Changes
Pull the latest changes from the remote repository to ensure you’re up to date:

```bash

git pull

```


---

### Folder: `04-git-workflow/workflow.md`

```markdown
# Git Workflow

A typical Git workflow involves a sequence of steps to modify, track, and collaborate on a project. Here’s a common development workflow using Git:

## Step 1: Modify Your Files
Start by making changes to your project in your **working directory**. These changes can involve editing existing files, adding new ones, or deleting old ones.

## Step 2: Stage Changes
After modifying your files, you decide which ones should be included in the next commit. Use the following command to add files to the **staging area**:
```bash
git add <file>
```

Or stage all changes:

```bash

git add .
```