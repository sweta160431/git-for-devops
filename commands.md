# Git Commands Cheat Sheet

## 1. Repository Setup

### Initialize a Git repository:
```bash
git init
```

### Clone a repository:
```bash
git clone <repository-url>
```

---

## 2. Configuration

### Set global user name:
```bash
git config --global user.name "Your Name"
```

### Set global user email:
```bash
git config --global user.email "youremail@example.com"
```

---

## 3. Checking Status

### Check the status of your working directory:
```bash
git status
```

---

## 4. Staging and Unstaging

### Add a file to the staging area:
```bash
git add <filename>
```

### Add all files to the staging area:
```bash
git add .
```

### Unstage a file:
```bash
git restore --staged <filename>
```

---

## 5. Committing Changes

### Commit staged changes:
```bash
git commit -m "commit message"
```

---

## 6. Branching

### List all branches:
```bash
git branch
```

### Create a new branch:
```bash
git checkout -b <branch-name>
```

### Switch to another branch:
```bash
git checkout <branch-name>
```

---

## 7. Merging

### Merge a branch into the current branch:
```bash
git merge <branch-name>
```

---

## 8. Viewing History

### Show commit history:
```bash
git log
```

### Show condensed commit history:
```bash
git log --oneline
```

---

## 9. Deleting Files

### Delete a file:
```bash
rm <filename>
git rm <filename>
```

---

## 10. Viewing Remote Repositories

### View remote repositories:
```bash
git remote -v
```

---

## 11. Push and Pull

### Push changes to a remote repository:
```bash
git push origin <branch-name>
```

### Pull changes from a remote repository:
```bash
git pull origin <branch-name>
```

---

## 12. Deleting Branches

### Delete a branch locally:
```bash
git branch -d <branch-name>
```

### Delete a branch remotely:
```bash
git push origin --delete <branch-name>
```

---

## 13. Undoing Changes

### Restore a file to its last committed state:
```bash
git restore <filename>
```

### Reset all changes in the working directory:
```bash
git reset --hard
```

