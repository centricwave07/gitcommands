# Git commands


# Setup and Configuration
git --version: Check the installed Git version.
git config --global user.name "Your Name": Set your name for all repositories.
git config --global user.email "youremail@example.com": Set your email for all repositories.
# Creating Repositories
git init: Initialize a new local Git repository in the current directory.
git clone [url]: Clone a repository into a new directory.
# Local Changes
git status: Show the working tree status.
git add [file]: Add a file to the staging area.
git add .: Add all new and changed files to the staging area.
git commit -m "Commit message": Commit changes with a message.
git commit -a -m "Commit message": Add changes from all tracked files and commit.
# Branching
git branch: List all local branches.
git branch [branch-name]: Create a new branch.
git checkout [branch-name]: Switch to the specified branch.
git checkout -b [branch-name]: Create and switch to a new branch.
git merge [branch-name]: Merge a branch into the active branch.
# Remote Repositories
git remote add [alias] [url]: Add a remote repository.
git remote -v: List remote repositories.
git push [alias] [branch]: Upload local repository content to a remote repository.
git pull [alias] [branch]: Update local repository with remote changes.
git fetch [alias]: Fetch changes from remote repository without merging.
# History and Logs
git log: Show the commit logs.
git log --oneline: Show the commit logs in a short format.
git blame [file]: Show who changed what and when in [file].
# Undo Changes
git reset [commit]: Reset the HEAD to a specific commit.
git revert [commit]: Create a new commit that undoes the changes made in a specific commit.
git restore [file]: Restore a file to a previous version.
# Advanced
git stash: Stash changes in a dirty working directory.
git stash apply: Apply changes from the stash.
git rebase [branch]: Reapply changes on top of another branch.
git cherry-pick [commit]: Apply changes from a specific commit to the current branch.
These are just the basics; Git offers many more functionalities. Each command usually has a range of options and flags that you can discover using git help [command].



