# Git Commands Handbook

A comprehensive guide to essential Git commands for every programmer's daily workflow.

## Introduction

Welcome to the Git Commands Handbook! This repository serves as a reference guide for common Git commands used in the daily life of a programmer. Whether you are a beginner or an experienced developer, you'll find a collection of commands to streamline your workflow and enhance your version control skills.

## Commands

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a new Git repository in a directory |
| `git clone ssh://git@github.com/<username>/<repository-name>.git` | Cloning the repository or configuring a remote in a local Git repository |
| `git status` | Show the status of changes as untracked, modified, or staged in your working directory |
| `git add . ` | Add all changes (new, modified, and deleted files) in the working directory to the staging area |
| `git add *.txt ` | Use patterns to add files that match a specific criteria (e.g add all `.txt` files)|
| `git add -A ` | Add all changes, including untracked files |
| `git add <file-name>` | Add a single file to the staging area |
| `git add <path\to\dir>` | Add changes only in a specific directory |
| `git commit -m "Your commit message here"` | Commit all staged changes with a message |
| `git commit -a -m "Your commit message here"` | Automatically stage and commit all changes (without git add) |



## Meaning of the terms used:

- Staging area is like a preview of the changes you're about to save. It allows you to carefully select and review modifications before making them a permanent part of your project's history
