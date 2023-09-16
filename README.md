# Git commands


# Setup and Configuration
1. <b>git --version:</b> Check the installed Git version.
2. <b>git config --global user.name "Your Name":</b> Set your name for all repositories.
3. <b>git config --global user.email "youremail@example.com":</b> Set your email for all repositories.
4. <b>git config user.name</b>
5. <b>git config --local user.name</b>
6. <b>git config --global user.name</b>
# Creating Repositories
1. <b>git init:</b> Initialize a new local Git repository in the current directory.
2. <b>git clone [url]:</b> Clone a repository into a new directory.
# Local Changes
1. <b>git status:</b> Show the working tree status.
2. <b>git add [file]:</b> Add a file to the staging area.
3. <b>git add .:</b> Add all new and changed files to the staging area.
4. <b>git commit -m "Commit message":</b> Commit changes with a message.
5. <b>git commit -a -m "Commit message":</b> Add changes from all tracked files and commit.
# Branching
1. <b>git branch:</b> List all local branches.
2. <b>git branch [branch-name]:</b> Create a new branch.
3. <b>git checkout [branch-name]:</b> Switch to the specified branch.
4. <b>git checkout -b [branch-name]:</b> Create and switch to a new branch.
5. <b>git merge [branch-name]:</b> Merge a branch into the active branch.
# Remote Repositories
1. <b>git remote add [alias] [url]:</b> Add a remote repository.
2. <b>git remote -v:</b> List remote repositories.
3. <b>git push [alias] [branch]:</b> Upload local repository content to a remote repository.
4. <b>git pull [alias] [branch]:</b> Update local repository with remote changes.
5  <b>git fetch [alias]:</b> Fetch changes from remote repository without merging.
# History and Logs
1. <b>git log:</b> Show the commit logs.
2. <b>git log --oneline:</b> Show the commit logs in a short format.
3. <b>git blame [file]:</b> Show who changed what and when in [file].
# Undo Changes
1. <b>git reset [commit]:</b> Reset the HEAD to a specific commit.
2. <b>git revert [commit]:</b> Create a new commit that undoes the changes made in a specific commit.
3. <b>git restore [file]:</b> Restore a file to a previous version.
# Advanced
1. <b>git stash:</b> Stash changes in a dirty working directory.
2. <b>git stash apply:</b> Apply changes from the stash.
3. <b>git rebase [branch]:</b> Reapply changes on top of another branch.
4. <b>git cherry-pick [commit]:</b> Apply changes from a specific commit to the current branch.
5. <b>git reset —hard HEAD:</b> For hard pull and ignore non committed file
6. These are just the basics; Git offers many more functionalities. Each command usually has a range of options and flags that you can discover using <b>git help [command].</b>



