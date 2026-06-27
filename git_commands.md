# Git Commands Cheat Sheet 🚀

A complete list of commonly used Git commands with explanations.

---

# 1. Configure Git

### Set username

```bash
git config --global user.name "Your Name"
```

Used to set your Git username.

### Set email

```bash
git config --global user.email "your@email.com"
```

Used to set your Git email.

### Check configuration

```bash
git config --list
```

Shows all Git configurations.

---

# 2. Initialize Repository

### Create new Git repository

```bash
git init
```

Initializes Git in current directory.

### Clone repository

```bash
git clone <repo-url>
```

Copies remote repository to local machine.

Example:

```bash
git clone https://github.com/user/repo.git
```

---

# 3. Check Status

### Check current status

```bash
git status
```

Shows modified, staged, and untracked files.

---

# 4. Add Files

### Add one file

```bash
git add filename
```

### Add all files

```bash
git add .
```

Moves changes to staging area.

---

# 5. Commit Changes

### Commit staged changes

```bash
git commit -m "message"
```

Example:

```bash
git commit -m "Added login feature"
```

Saves changes in local repository.

---

# 6. View History

### Show commit history

```bash
git log
```

### One line history

```bash
git log --oneline
```

Shows previous commits.

---

# 7. Branching

### Show branches

```bash
git branch
```

### Create branch

```bash
git branch branch-name
```

### Switch branch

```bash
git checkout branch-name
```

### Create and switch branch

```bash
git checkout -b branch-name
```

### Delete branch

```bash
git branch -d branch-name
```

---

# 8. Merging

### Merge branch

```bash
git merge branch-name
```

Merges selected branch into current branch.

---

# 9. Remote Repository

### Show remote URL

```bash
git remote -v
```

### Add remote repository

```bash
git remote add origin <repo-url>
```

Example:

```bash
git remote add origin https://github.com/user/repo.git
```

---

# 10. Push Changes

### Push branch

```bash
git push origin branch-name
```

Example:

```bash
git push origin main
```

Uploads local commits to GitHub.

### Push first time

```bash
git push -u origin main
```

Sets upstream branch.

---

# 11. Pull Changes

### Pull latest changes

```bash
git pull origin main
```

Downloads and merges latest changes.

---

# 12. Fetch Changes

### Fetch updates

```bash
git fetch
```

Downloads changes without merging.

---

# 13. Undo Changes

### Remove from staging

```bash
git reset filename
```

### Discard local changes

```bash
git checkout -- filename
```

### Reset commit

```bash
git reset --soft HEAD~1
```

Undo commit but keep changes.

---

# 14. Stash

### Save temporary changes

```bash
git stash
```

### View stash list

```bash
git stash list
```

### Restore stash

```bash
git stash pop
```

Used to save work temporarily.

---

# 15. Tags

### Create tag

```bash
git tag v1.0
```

### Show tags

```bash
git tag
```

Used for version releases.

---

# 16. Helpful Commands

### Show differences

```bash
git diff
```

### Show staged differences

```bash
git diff --staged
```

### Remove file

```bash
git rm filename
```

### Rename file

```bash
git mv oldname newname
```

---

# Basic Git Workflow

```bash
git init
git add .
git commit -m "First commit"
git remote add origin <repo-url>
git push -u origin main
```

---

# Daily Workflow

```bash
git pull origin main
git status
git add .
git commit -m "Updated project"
git push origin main
```

---

Happy Coding 🚀
