# GitHub-Intro

## Step 1: 

First, initialize a git repo. Navigatge to your project where you would be making the changes and the creation of the repo then run this: 

```
git init
```

The git init command initializes a new Git repository in a directory, setting it up for version control. 
It creates a hidden .git directory to store repository information and configuration, establishes an initial branch (usually "main" or "master"), and enables tracking of file changes.
This command is used to start managing the version history of your project and is the first step when setting up a Git repository.

## Step 2: 

Create a new file, and verify its status: 
```
touch example_file.html
git branch
```

The command touch example_file.html is used to create an empty HTML file named "example_file.html."

The command git branch is used to list all the branches in a Git repository, showing the current branch with an asterisk (*) and other branches alongside it. 
This command is used to view the available branches in the repository.

## Step 3: 

Create a commit: 

```
git commit -m
```

The git commit -m command is used to create a new commit in a Git repository with a specified commit message (-m). 
This message is a brief description of the changes made in the commit, allowing you to document the purpose and context of the changes. 
Commits are essential for tracking the history of a project and collaborating with others, and the commit message provides a concise explanation of what was done in that specific commit.

## Step 4: 

Branch Creation: 

```
git branch branch_name
```

The above command creates a new branch apart of the main/master. 

```
git branch
```

Git branch, confirms the creation of the branch

## Step 5: 

Create a new repository

If you don't know how to create a new repository that is okay. You can navigate to: <i>[https://github.com/AlexMitev21/Repository-Creation]</i>

Now on the local machine, open the terminal, and run: 

```
git remote add origin https://github.com/AlexMitev21/Repository-Creation.git
```

This command adds a remote repository named "origin" and associates it with the GitHub repository's URL. It establishes a connection between the local and remote repositories.

```
git push -u origin master
```
This command pushes the local "master" branch to the "origin" remote repository, updating the remote repository with the changes made locally. The -u flag sets up tracking, so in the future, you can simply use git push or git pull without specifying the remote and branch names.

## Step 6: 

Push a Branch

```
git push origin my-new-branch
```
The command is used to push the changes from a local branch (in this case, "my-new-branch") to a branch with the same name in a remote repository named "origin."

It uploads your local branch's changes to the corresponding branch in the remote repository, keeping them in sync. This is commonly used when you want to share your local changes or collaborate with others on a specific branch in a remote Git repository.

## Step 7:

Confirm your changes on the local machine: 

```
git pull origin master 
```

The command is used to fetch and integrate changes from a remote repository's "master" branch into your local branch.

```
git log
```
See all of the new commits 


