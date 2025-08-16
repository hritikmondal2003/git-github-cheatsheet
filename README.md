# 🐙 GitHub Cheat Codes – Git CLI + GitHub Tips

A quick reference guide for essential Git and GitHub commands.

---

## ⚙️ SETUP

| Command | Description |
|---------|-------------|
| `git config --global user.name "Your Name"` | Set your name |
| `git config --global user.email "your@email.com"` | Set your email |
| `git config --global init.defaultBranch main` | Use `main` as default branch |

---

## 📂 CREATE / CLONE

| Command | Description |
|---------|-------------|
| `git init` | Initialize a local repo |
| `git clone <repo_url>` | Clone a GitHub repository |

---

## 🔄 BASIC WORKFLOW

| Command | Description |
|---------|-------------|
| `git status` | Show status of working directory |
| `git add <file>` | Stage file |
| `git add .` | Stage all changes |
| `git commit -m "msg"` | Commit with message |
| `git push` | Push changes to remote |
| `git pull` | Pull latest changes from remote |

---

## 🌿 BRANCHING

| Command | Description |
|---------|-------------|
| `git branch` | List all branches |
| `git branch <name>` | Create new branch |
| `git checkout <name>` | Switch to branch |
| `git checkout -b <name>` | Create + switch to branch |
| `git merge <branch>` | Merge a branch into current |
| `git branch -d <name>` | Delete branch |

---

## 🌐 REMOTE

| Command | Description |
|---------|-------------|
| `git remote -v` | View remote repos |
| `git remote add origin <url>` | Link local repo to GitHub |
| `git push -u origin main` | Push and set upstream |

---

## 🛠️ UNDO & FIX

| Command | Description |
|---------|-------------|
| `git restore <file>` | Undo changes to a file |
| `git restore --staged <file>` | Unstage a file |
| `git reset --soft HEAD~1` | Undo last commit (keep files) |
| `git reset --hard HEAD~1` | Undo last commit (discard files) |
| `git log` | Show commit history |
| `git diff` | Show unstaged changes |
| `git diff --staged` | Show staged changes |

---

## 🏷️ TAGS

| Command | Description |
|---------|-------------|
| `git tag` | List tags |
| `git tag <name>` | Create a tag |
| `git push origin <tag>` | Push tag to remote |

---

## 📦 STASH

| Command | Description |
|---------|-------------|
| `git stash` | Temporarily save changes |
| `git stash list` | List stashed changes |
| `git stash pop` | Reapply stash |
| `git stash drop` | Delete stash |

---

## 📋 GITHUB WORKFLOW EXAMPLE

```bash
git init
git remote add origin <repo_url>
git add .
git commit -m "Initial commit"
git push -u origin main
