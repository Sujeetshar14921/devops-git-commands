# Git DevOps CheatSheet

A complete collection of the most commonly used Git commands in DevOps, CI/CD pipelines, and real-world development workflows.

---

# 🚀 Most Used Workflow While Pushing Code

These are the commands developers use most frequently during daily development.

## 1. Check Current Status

Shows modified, staged, and untracked files.

```bash
git status
```

### 📌 Why Use?
- Check changed files
- Verify staging status
- Check current branch

---

## 2. Pull Latest Code

Downloads latest code before starting work.

```bash
git pull origin main
```

### 📌 Why Use?
- Prevent conflicts
- Sync team updates
- Get latest production code

---

## 3. Create New Branch

Creates a separate branch for features or bug fixes.

```bash
git checkout -b feature-auth
```

### 📌 Why Use?
- Safe feature development
- Team collaboration
- Clean workflow

---

## 4. Add Files to Staging

Adds updated files for commit.

```bash
git add .
```

### 📌 Why Use?
- Prepare files for commit
- Track project changes

---

## 5. Commit Changes

Saves changes locally with a message.

```bash
git commit -m "Added authentication feature"
```

### 📌 Why Use?
- Save development progress
- Maintain project history

---

## 6. Push Code to GitHub

Uploads local commits to remote repository.

```bash
git push origin feature-auth
```

### 📌 Why Use?
- Upload code to GitHub
- Trigger CI/CD pipelines
- Create Pull Requests

---

# 🔥 Complete Daily DevOps Workflow

```bash
git pull origin main
git checkout -b feature-auth
git add .
git commit -m "Added auth feature"
git push origin feature-auth
```

---

# 🌿 Branch Management Commands

## Switch Branch

```bash
git checkout main
```

### 📌 Use For
- Switching branches
- Returning to main branch

---

## Merge Branch

```bash
git merge feature-auth
```

### 📌 Use For
- Combining feature code
- Release workflows

---

## Rebase Branch

```bash
git rebase main
```

### 📌 Use For
- Clean commit history
- Updating feature branch

---

# 📦 Repository Setup Commands

## Clone Repository

Downloads project from GitHub.

```bash
git clone <repo-url>
```

### 📌 Use For
- Starting new project
- Downloading company repositories

---

## Add Remote Repository

Connects local project to GitHub.

```bash
git remote add origin <repo-url>
```

### 📌 Use For
- First-time GitHub setup
- Connecting local project

---

## Check Remote URL

Displays connected repository URL.

```bash
git remote -v
```

### 📌 Use For
- Verify connected repository
- Debug remote issues

---

## Change Remote URL

Updates repository path.

```bash
git remote set-url origin <new-url>
```

### 📌 Use For
- Repository migration
- GitHub account change

---

## Remove Remote URL

Disconnects current repository.

```bash
git remote remove origin
```

### 📌 Use For
- Remove wrong repository
- Reset Git connection

---

# 🛠️ Code Recovery & Cleanup Commands

## Stash Changes

Temporarily saves uncommitted changes.

```bash
git stash
```

### 📌 Use For
- Emergency branch switching
- Temporary save

---

## Restore Stash

Restores stashed changes.

```bash
git stash pop
```

### 📌 Use For
- Continue previous work

---

## Reset Changes

Removes commits and restores previous state.

```bash
git reset --hard HEAD~1
```

### 📌 Use For
- Undo bad commits
- Remove broken code

⚠️ Warning:
Deletes local changes permanently.

---

## Reset to Remote Repository

Makes local project exactly like GitHub repository.

```bash
git reset --hard origin/main
```

### 📌 Use For
- Fix broken local code
- Sync production code

---

## Restore File

Restores original file content.

```bash
git restore <file-name>
```

### 📌 Use For
- Undo accidental file changes

---

## Remove Untracked Files

Deletes unwanted files and folders.

```bash
git clean -fd
```

### 📌 Use For
- Project cleanup
- Remove temporary files

---

# 📜 Logs & History Commands

## View Commit History

```bash
git log --oneline
```

### 📌 Use For
- Debugging
- Finding commit IDs
- Deployment tracking

---

## Reflog

Shows complete Git history.

```bash
git reflog
```

### 📌 Use For
- Recover deleted commits
- Restore lost branches

---

# 🚀 Release Commands

## Create Version Tag

```bash
git tag v1.0.0
```

### 📌 Use For
- Production releases
- Version management

---

## Push Tags

```bash
git push origin --tags
```

### 📌 Use For
- Publish release versions
- Deployment automation

---

# 🔥 Most Common DevOps Commands

```bash
git status
git pull origin main
git checkout -b feature-name
git add .
git commit -m "message"
git push origin branch-name
git merge branch-name
git rebase main
git stash
git log --oneline
git remote -v

---

# 📌 Why This Repository?

Useful for:

- DevOps Engineers
- Frontend Developers
- Backend Developers
- Full Stack Developers
- CI/CD Learning
- Git Beginners

---

# ⭐ Support

If this repository helped you, give it a ⭐ on GitHub.

---

# 👨‍💻 Author

Sujeet Sharma
