# Git Commands Reference

## 1. Setup & Configuration

| Command | Usage | Example |
|---------|-------|---------|
| `git init` | Initializes a new Git repository in the current directory. | `git init` |
| `git config --global user.name "username"` | Sets your Git username for all repositories. | `git config --global user.name "alank8s"` |
| `git config --global user.email "email@example.com"` | Sets your Git email address for all repositories. | `git config --global user.email "alank8s.cloud@gmail.com"` |

---

## 2. Basic Workflow

| Command | Usage | Example |
|---------|-------|---------|
| `git add <file>` | Adds specific files to the staging area. | `git add index.html` |
| `git add .` | Adds all modified and new files to the staging area. | `git add .` |
| `git commit -m "message"` | Creates a new commit with a descriptive message. | `git commit -m "Added login page"` |
| `git push origin <branch>` | Uploads local commits to the remote repository. | `git push origin main` |
| `git branch <branch-name>` | Creates a new branch. | `git branch feature-login` |
| `git switch <branch-name>` | Switches to an existing branch. | `git switch feature-login` |
| `git switch -c <branch-name>` | Creates a new branch and switches to it immediately. | `git switch -c feature-auth` |

---

## 3. Viewing Changes

| Command | Usage | Example |
|---------|-------|---------|
| `git status` | Displays the current state of the working directory and staging area. | `git status` |
| `git log` | Shows the commit history. | `git log` |
| `git log --oneline` | Shows a compact one-line commit history. | `git log --oneline` |
| `git diff` | Displays unstaged changes between the working directory and the staging area. | `git diff` |
| `git diff --staged` | Displays staged changes that will be included in the next commit. | `git diff --staged` |


# Git Branching & Remote Commands

## Branching

| Command | Usage |
|---------|-------|
| `git branch` | Lists all local branches. |
| `git branch <branch-name>` | Creates a new branch. |
| `git switch <branch-name>` | Switches to an existing branch. |
| `git switch -c <branch-name>` | Creates a new branch and switches to it. |
| `git branch -d <branch-name>` | Deletes a merged branch safely. |
| `git branch -D <branch-name>` | Force deletes a branch. |

---

## Commit History & Status

| Command | Usage |
|---------|-------|
| `git status` | Shows the current status of the working directory and staging area. |
| `git log` | Displays the complete commit history. |
| `git log --oneline` | Displays a compact one-line commit history. |

---

## Comparing Changes

| Command | Usage |
|---------|-------|
| `git diff` | Shows unstaged changes. |
| `git diff --staged` | Shows staged changes waiting to be committed. |

---

## Working with Remotes

| Command | Usage |
|---------|-------|
| `git remote -v` | Lists all configured remote repositories. |
| `git remote add origin <repository-url>` | Adds a remote repository named `origin`. |
| `git remote add upstream <repository-url>` | Adds the original repository as `upstream`. |

---

## Push & Pull

| Command | Usage |
|---------|-------|
| `git push origin <branch>` | Pushes commits to the remote branch. |
| `git push -u origin <branch>` | Pushes the branch and sets it as the default upstream. |
| `git pull origin <branch>` | Downloads and merges changes from the remote branch. |
| `git fetch origin` | Downloads changes without merging them. |
| `git fetch upstream` | Downloads updates from the upstream repository. |
| `git merge upstream/main` | Merges upstream changes into the current branch. |

---

## Clone

| Command | Usage |
|---------|-------|
| `git clone <repository-url>` | Creates a local copy of a remote repository. |

