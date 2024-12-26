# Git and GitHub: A Complete Guide

This repository was created to learn Git and GitHub more practically by implementing all commands.\
I have included all of the concepts I have learned in this readme file, do use it.

---

## Table of Contents
1. [What is Git?](#what-is-git)
2. [What is GitHub?](#what-is-github)
3. [Installing Git](#installing-git)
4. [Configuring Git](#configuring-git)
5. [Basic Git Workflow](#basic-git-workflow)
6. [Important Git Commands](#important-git-commands)
7. [Branching and Merging](#branching-and-merging)
8. [Remote Repositories](#remote-repositories)
9. [Stashing and Cleaning](#stashing-and-cleaning)
10. [Git Logs and History](#git-logs-and-history)
11. [GitHub Workflow](#github-workflow)
12. [Collaborating on GitHub](#collaborating-on-github)
13. [Advanced Git Commands](#advanced-git-commands)
14. [Troubleshooting Git Issues](#troubleshooting-git-issues)
15. [Resources](#resources)

---

## 1. What is Git?
Git is a distributed version control system designed to track changes in source code efficiently. It enables multiple developers to collaborate on projects by maintaining version histories and managing branches.

## 2. What is GitHub?
GitHub is a web-based platform for version control and collaboration using Git. It provides hosting for Git repositories and adds features like pull requests, issue tracking, and project management tools.

---

## 3. Installing Git

1. **Windows:** Download from [git-scm.com](https://git-scm.com/) and follow the installer.
2. **Mac:** Use Homebrew: `brew install git`.
3. **Linux:** Use the package manager:
   ```bash
   sudo apt-get install git # Debian/Ubuntu
   sudo yum install git     # RHEL/CentOS
   ```

Verify installation:
```bash
git --version
```

---

## 4. Configuring Git

Set up your identity:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

Check configuration:
```bash
git config --list
```

---

## 5. Basic Git Workflow
1. **Initialize a repository:**
   ```bash
   git init
   ```
2. **Add files to staging area:**
   ```bash
   git add <file>
   git add . # Add all changes
   ```
3. **Commit changes:**
   ```bash
   git commit -m "Commit message"
   ```
4. **Push to remote repository:**
   ```bash
   git push origin main
   ```

---

## 6. Important Git Commands

### Create a new repository
```bash
git init
```

### Clone a repository
```bash
git clone <repository-url>
```

### Check repository status
```bash
git status
```

### Stage changes
```bash
git add <file>
git add .
```

### Commit changes
```bash
git commit -m "Your message here"
```

### View commit history
```bash
git log
```

### View specific file changes
```bash
git diff
```

---

## 7. Branching and Merging

### Create a branch
```bash
git branch <branch-name>
```

### Switch to a branch
```bash
git checkout <branch-name>
```

### Create and switch to a branch
```bash
git checkout -b <branch-name>
```

### Merge a branch
```bash
git merge <branch-name>
```

### Delete a branch
```bash
git branch -d <branch-name>
```

---

## 8. Remote Repositories

### Add a remote repository
```bash
git remote add origin <repository-url>
```

### View remotes
```bash
git remote -v
```

### Push changes to a remote repository
```bash
git push origin <branch-name>
```

### Pull changes from a remote repository
```bash
git pull origin <branch-name>
```

---

## 9. Stashing and Cleaning

### Stash changes
```bash
git stash
```

### Apply stashed changes
```bash
git stash apply
```

### Drop a stash
```bash
git stash drop
```

### Clean untracked files
```bash
git clean -f
```

---

## 10. Git Logs and History

### Show commit history
```bash
git log
```

### Show one-line summary of commits
```bash
git log --oneline
```

### Show graphical representation
```bash
git log --graph --oneline --all
```

---

## 11. GitHub Workflow

1. Create a repository on GitHub.
2. Clone it locally:
   ```bash
   git clone <repository-url>
   ```
3. Make changes, stage, and commit:
   ```bash
   git add .
   git commit -m "Description of changes"
   ```
4. Push changes:
   ```bash
   git push origin main
   ```

---

## 12. Collaborating on GitHub

### Fork a repository
1. Click "Fork" on GitHub.
2. Clone your fork:
   ```bash
   git clone <fork-url>
   ```

### Open a pull request
1. Commit changes to your fork.
2. Push changes and click "Pull Request" on GitHub.

---

## 13. Advanced Git Commands

### Revert a commit
```bash
git revert <commit-hash>
```

### Reset to a previous commit
```bash
git reset --hard <commit-hash>
```

### Rebase
```bash
git rebase <branch>
```

### Cherry-pick a commit
```bash
git cherry-pick <commit-hash>
```

---

## 14. Troubleshooting Git Issues

### Undo the last commit
```bash
git reset --soft HEAD~1
```

### Resolve merge conflicts
1. Edit conflicted files.
2. Add changes:
   ```bash
   git add <file>
   ```
3. Commit:
   ```bash
   git commit
   ```

### Check unmerged files
```bash
git status
```

---

## 15. Resources
[Git and GitHub for Beginners - Crash Course | freeCodeCamp](https://youtu.be/RGOj5yH7evk?si=-5O2bfziUUlONquI)
[Git and GitHub learning resources | GitHub](https://docs.github.com/en/get-started/start-your-journey/git-and-github-learning-resources)


This README aims to serve as a quick reference for all key Git and GitHub concepts. Happy coding!
