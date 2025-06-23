# Git Branching Learning Repo 🌿

This repo is created to help you understand and practice **Git branching workflows**.

---

## 🔧 Basic Git Branching Commands

Here are the most commonly used Git commands when working with branches:

```bash
# Check current branch
git branch

# Create a new branch
git branch <branch-name>

# Switch to a different branch
git checkout <branch-name>

# Create and switch to a new branch in one command (Git 2.23+)
git switch -c <branch-name>

# Push a local branch to remote (GitHub)
git push origin <branch-name>

# List all remote branches
git branch -r

# Delete a local branch
git branch -d <branch-name>

# Force delete a local branch (if it has unmerged changes)
git branch -D <branch-name>

# Delete a remote branch
git push origin -d <branch-name>

# Merge a branch into current branch
git merge <branch-name>

# Rebase current branch onto another
git rebase <branch-name>
```

# Using VS Code

```bash
ctrl + shift + p
```

To delete a branch use

```bash
git:Delete Branch
```

To sync a branch use

```bash
git:Fetch(Prune)
```
