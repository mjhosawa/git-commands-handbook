## Git Commands Handbook

This guide provides easy-to-use Git commands with simple explanation that have been my go-to tools throughout my coding journey. 

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a new Git repository in a directory. |
| `git clone ssh://git@github.com/<username>/<repo-name>.git` | Cloning the repository or configuring a remote in a local Git repository. |
| `git status` | Show the status of changes as untracked, modified, or staged in your working directory. |
| `git add . ` | Add all changes (new, modified, and deleted files) in the working directory to the staging area. |
| `git add *.txt ` | Use patterns to add files that match a specific criteria (e.g add all `.txt` files)|
| `git add -A ` | Add all changes, including untracked files. |
| `git add <filename>` | Add a single file to the staging area. |
| `git add <path\to\dir>` | Add changes only in a specific directory. |
| `git commit -m "Your commit message here"` | Commit all staged changes with a message. |
| `git commit -a -m "Your commit message here"` | Automatically stage and commit all changes (without `git add`) |
| `git commit --amend -m "New message"` | Add more changes to the last commit or update its message. |
| `git commit --date="YYYY-MM-DD HH:MM:SS" -m "Your message"` | Commit with a custom date and time. |
| `git log` | See a concise log of commits. |
| `git log --oneline` | Display each commit on one line. |
| `git log --pretty=format:"%h %an %ad %s"` | Include author and date information. |
| `git log -- <filename>` | See commits related to a specific file. |
| `git diff` | See the changes in your working directory compared to the last commit. |
| `git diff --staged` | Preview changes staged for the next commit. |
| `git diff <filename>` | Check modifications in a specific file. |
| `git diff <branch1>..<branch2>` | Compare changes between two branches. |
| `git push origin <branchname>` | Push the changes made in a local branch to a remote repository. |
| `git push -u origin <branchname>` | Push the changes made in a local branch to a remote repository and set up a tracking relationship between the local and remote branch. |
| `git push` | Push your committed changes to the remote repository. |
| `git push -f` | Forcefully push local changes to the remote repository, overwriting any changes that may exist there. |
| `git push origin -d <branchname>` | Delete a remote branch on the Git repository. |
| `git pull` | Gets the latest changes from the remote repository and merges into current branch. |
| `git pull origin <branchname>` | Gets the latest changes from the remote repository's specific branch and merges into current branch. |
| `git pull --all` | Gets the latest changes from all the remotes and merges the fetched changes into the corresponding branches in the local repository. |
| `git pull --rebase` | Gets the latest changes from the remote repository and rebase the current branch on top of the fetched changes, instead of creating a merge commit. |
| `git pull --no-commit` | Gets the latest changes from the remote repository and merges them into the current branch but doesn't create a commit automatically. It lets you review the changes before committing. |
| `git checkout -b <branchname>` | Create and move to a new branch in one step. |
| `git checkout <branchname>` | Move to an existing branch. |
| `git checkout -- <filename>` | Undo changes in a specific file. |
| `git checkout -- . ` | Discard all changes in your working directory. |
| `git checkout -` | Return to the branch you were on before. |
| `git checkout <commit-hash>` | Check out a specific commit detached HEAD state. |
| `git checkout -b <local_branchname> <origin/remote_branchname>` | Switch to a remote branch (creates a local tracking branch) |
| `git checkout <commit-hash> -- <filename>` | Switch to a specific version of a file from a commit. |
| `git restore --source=HEAD --staged --worktree .` | Undo changes made to all files (equivalent to `git checkout -- .`) |
| `git restore --source=HEAD --staged --worktree <filename>` | Undo changes made to a file (equivalent to `git checkout -- <filename>`) |
| `git remote` | Lists all the remote repositories associated with the local repository |
| `git remote add origin ssh://git@github.com/<username>/<repo-name>.git` | Add a remote repository. |
| `git remote rename <old-name> <new-name>` | Renames a remote repository from an old name to new name in local repository. |
| `git rm <filename>` | Removes the specific file from both the working directory and the staging area. Way to tell Git to stop tracking a file. |
| `git rm --dry-run <filename>` | Performs a dry run of the removal operation. |
| `git rm -r <dir>` | Removes recursively the directory and its contents from both the working directory and the staging area. Used when you want to delete an entire directory from your project. |
| `git rm --cached <filename>` | Removes the specific file from the staging area but keeps in the working directory. Way to tell Git to stop tracking a file but keep in the local filesystem. |
| `git rm --cached -r <dir>` | Removes recursively the directory and its contents from the staging area but keeps in the working directory. Used to stop tracking a directory and its contents but keep in the local filesystem. |
| `git cherry-pick <commit-hash>` | Used to apply specific commit from one branch onto another branch. |


## Meaning of the terms used in the commands:

- Staging area is like a preview of the changes you're about to save. It allows you to carefully select and review modifications before making them a permanent part of your project's history.
- Tracking relationship between a local and a remote branch meaning it simplifies tasks like pushing and pulling changes, allowing you to interact with the remote branch without specifying its name each time.
- "detached HEAD" state means that you are not on any branch but are directly looking at a specific historical point in your project.


## Project Status

[![Project Status: Active](https://img.shields.io/badge/Project%20Status-Active-green.svg)](https://github.com/mjhosawa/git-commands-handbook)
