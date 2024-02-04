# Git Commands Handbook

This guide is here to help everyone, whether you're just starting out or have been coding for a while. It's a quick reference for Git commands that make your work easier and improve your skills in managing different versions of your code

## Commands

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a new Git repository in a directory |
| `git clone ssh://git@github.com/<username>/<repository-name>.git` | Cloning the repository or configuring a remote in a local Git repository |
| `git status` | Show the status of changes as untracked, modified, or staged in your working directory |
| `git add . ` | Add all changes (new, modified, and deleted files) in the working directory to the staging area |
| `git add *.txt ` | Use patterns to add files that match a specific criteria (e.g add all `.txt` files)|
| `git add -A ` | Add all changes, including untracked files |
| `git add <filename>` | Add a single file to the staging area |
| `git add <path\to\dir>` | Add changes only in a specific directory |
| `git commit -m "Your commit message here"` | Commit all staged changes with a message |
| `git commit -a -m "Your commit message here"` | Automatically stage and commit all changes (without git add) |
| `git commit --amend -m "New message"` | Add more changes to the last commit or update its message |
| `git commit --date="YYYY-MM-DD HH:MM:SS" -m "Your message"` | Commit with a custom date and time |
| `git log` | See a concise log of commits |
| `git log --oneline` | Display each commit on one line |
| `git log --pretty=format:"%h %an %ad %s"` | Include author and date information |
| `git log -- <filename>` | See commits related to a specific file |
| `git diff` | See the changes in your working directory compared to the last commit |
| `git diff --staged` | Preview changes staged for the next commit |
| `git diff <filename>` | Check modifications in a specific file |


## Meaning of the terms used:

- Staging area is like a preview of the changes you're about to save. It allows you to carefully select and review modifications before making them a permanent part of your project's history
