# Git Workflow: Keeping Your Repo in Sync

This is a clear step-by-step guide to keep your local project and GitHub repository up to date. Whether you're making changes on GitHub or in VSCode, following this workflow ensures your files stay in sync and prevents conflicts.

## 1. Pull Latest Changes from GitHub (Before Making Local Changes)
Run this first to ensure your local repo is up to date:

`git pull origin main`

## 2. Make & Save Changes Locally

Edit files in VSCode as needed.

## 3. Stage Changes
Add modified or new files to the staging area:

`git add .`

## 4.Commit Your Changes
Write a commit message describing what you changed:

`git commit -m "Your commit message here"`

## 5.Push Changes to GitHub
Upload your local changes to the remote repository:

`git push origin main`

📌 ##Key Habit:
-Always pull before you start working.

-Use `git status` to list all new or modified files that haven't yet been committed.

-Push your changes frequently to keep everything in sync.

-If you make changes on GitHub, pull them before making local changes.