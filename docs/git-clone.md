# Cloning a GitHub Repository with All Branches

This is a clear step-by-step guide to cloning a GitHub repository along with all its branches. This ensures you have access to every branch in your project and can switch between them as needed.

## 1. Clone the Repository and Fetch All Branches

By default, `git clone` only pulls the main branch. To ensure you get all branches, use:

```sh
git clone <repo-url>
cd <repo-folder>
git fetch --all
```

Alternatively, if you want a mirrored or bare version:

```sh
git clone --mirror <repo-url>
```

or

```sh
git clone --bare <repo-url>
```

## 2. List All Available Branches

To see all branches, including remote ones:

```sh
git branch -a
```

This will display:

- **Local branches** (without `remotes/origin/` prefix)
- **Remote branches** (with `remotes/origin/` prefix)

## 3. Checkout and Track Remote Branches

If you need a specific branch that isn't checked out yet, create a local copy:

```sh
git checkout -b <branch-name> origin/<branch-name>
```

To switch between existing local branches:

```sh
git checkout <branch-name>
```

## 4. Pull the Latest Changes for All Branches

To ensure your branches are updated with the latest changes from GitHub:

```sh
git pull --all
```

## 📌 Key Habits:

- Always fetch and pull changes before working.
- Use `git branch -a` to verify which branches exist.
- Use `git checkout <branch-name>` to switch between branches.
- Frequently push changes to keep your branches up to date.

By following these steps, you'll have all the branches from your GitHub repository and can manage them effectively in your local environment.
