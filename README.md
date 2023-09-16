# Git commands


# Setup and Configuration
1. git --version: Check the installed Git version.
2. git config --global user.name "Your Name": Set your name for all repositories.
3. git config --global user.email "youremail@example.com": Set your email for all repositories.
# Creating Repositories
1. git init: Initialize a new local Git repository in the current directory.
2. git clone [url]: Clone a repository into a new directory.
# Local Changes
1. git status: Show the working tree status.
2. git add [file]: Add a file to the staging area.
3. git add .: Add all new and changed files to the staging area.
4. git commit -m "Commit message": Commit changes with a message.
5. git commit -a -m "Commit message": Add changes from all tracked files and commit.
# Branching
1. git branch: List all local branches.
2. git branch [branch-name]: Create a new branch.
3. git checkout [branch-name]: Switch to the specified branch.
4. git checkout -b [branch-name]: Create and switch to a new branch.
5. git merge [branch-name]: Merge a branch into the active branch.
# Remote Repositories
1. git remote add [alias] [url]: Add a remote repository.
2. git remote -v: List remote repositories.
3. git push [alias] [branch]: Upload local repository content to a remote repository.
4. git pull [alias] [branch]: Update local repository with remote changes.
5 .git fetch [alias]: Fetch changes from remote repository without merging.
# History and Logs
1. git log: Show the commit logs.
2. git log --oneline: Show the commit logs in a short format.
3. git blame [file]: Show who changed what and when in [file].
# Undo Changes
1. git reset [commit]: Reset the HEAD to a specific commit.
2. git revert [commit]: Create a new commit that undoes the changes made in a specific commit.
3. git restore [file]: Restore a file to a previous version.
# Advanced
1. git stash: Stash changes in a dirty working directory.
2. git stash apply: Apply changes from the stash.
3. git rebase [branch]: Reapply changes on top of another branch.
4. git cherry-pick [commit]: Apply changes from a specific commit to the current branch.
5. 
These are just the basics; Git offers many more functionalities. Each command usually has a range of options and flags that you can discover using ##git help [command].



