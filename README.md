# Git Commands Handbook

This guide provides easy-to-use Git commands with simple explanation that have been my go-to tools throughout my coding journey. 

## Commands

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a new Git repository in a directory |
| `git clone ssh://git@github.com/<username>/<repo-name>.git` | Cloning the repository or configuring a remote in a local Git repository |
| `git status` | Show the status of changes as untracked, modified, or staged in your working directory |
| `git add . ` | Add all changes (new, modified, and deleted files) in the working directory to the staging area |
| `git add *.txt ` | Use patterns to add files that match a specific criteria (e.g add all `.txt` files)|
| `git add -A ` | Add all changes, including untracked files |
| `git add <filename>` | Add a single file to the staging area |
| `git add <path\to\dir>` | Add changes only in a specific directory |
| `git commit -m "Your commit message here"` | Commit all staged changes with a message |
| `git commit -a -m "Your commit message here"` | Automatically stage and commit all changes (without `git add`) |
| `git commit --amend -m "New message"` | Add more changes to the last commit or update its message |
| `git commit --date="YYYY-MM-DD HH:MM:SS" -m "Your message"` | Commit with a custom date and time |
| `git log` | See a concise log of commits |
| `git log --oneline` | Display each commit on one line |
| `git log --pretty=format:"%h %an %ad %s"` | Include author and date information |
| `git log -- <filename>` | See commits related to a specific file |
| `git diff` | See the changes in your working directory compared to the last commit |
| `git diff --staged` | Preview changes staged for the next commit |
| `git diff <filename>` | Check modifications in a specific file |
| `git diff <branch1>..<branch2>` | Compare changes between two branches |
| `git push origin <branchname>` | Push the changes made in a local branch to a remote repository |
| `git push -u origin <branchname>` | Push the changes made in a local branch to a remote repository and set up a tracking relationship between the local and remote branch |
| `git push` | Push your committed changes to the remote repository |
| `git push -f` | Forcefully push local changes to the remote repository, overwriting any changes that may exist there. |
| `git push origin -d <branchname>` | Delete a remote branch on the Git repository |
| `git checkout -b <branchname>` | Create and move to a new branch in one step |
| `git checkout <branchname>` | Move to an existing branch |
| `git checkout -- <filename>` | Undo changes in a specific file |
| `git checkout -- . ` | Discard all changes in your working directory |
| `git checkout -` | Return to the branch you were on before |


## Meaning of the terms used in the commands:

- Staging area is like a preview of the changes you're about to save. It allows you to carefully select and review modifications before making them a permanent part of your project's history.
- Tracking relationship between a local and a remote branch meaning it simplifies tasks like pushing and pulling changes, allowing you to interact with the remote branch without specifying its name each time.


## Updates in Progress

This project is actively maintained, and updates are still in progress.

## Last Updated

This README was last updated on 5th February, 2024.

## Project Status

[![Project Status: Active](https://img.shields.io/badge/Project%20Status-Active-green.svg)](https://github.com/mjhosawa/git-commands-handbook)
