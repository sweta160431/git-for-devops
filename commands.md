# Git Commands Cheat Sheet

## 1. Repository Setup
- **Initialize a Git repository:**
  ```bash
  git init
Clone a repository:
bash
Copy code
git clone <repository-url>
2. Checking Status
Check the status of your working directory:
bash
Copy code
git status
3. Staging and Unstaging
Add a file to the staging area:

bash
Copy code
git add <filename>
Add all files to the staging area:

bash
Copy code
git add .
Unstage a file:

bash
Copy code
git restore --staged <filename>
4. Committing Changes
Commit staged changes:
bash
Copy code
git commit -m "commit message"
5. Branching
List all branches:

bash
Copy code
git branch
Create a new branch:

bash
Copy code
git checkout -b <branch-name>
Switch to another branch:

bash
Copy code
git checkout <branch-name>
6. Merging
Merge a branch into the current branch:
bash
Copy code
git merge <branch-name>
7. Viewing History
Show commit history:

bash
Copy code
git log
Show condensed commit history:

bash
Copy code
git log --oneline
8. Deleting Files
Delete a file:
bash
Copy code
rm <filename>
git rm <filename>
9. Configurations
Set global user email:

bash
Copy code
git config --global user.email "youremail@example.com"
Set global user name:

bash
Copy code
git config --global user.name "Your Name"
10. Viewing Remote Repositories
View remote repositories:
bash
Copy code
git remote -v
11. Push and Pull
Push changes to a remote repository:

bash
Copy code
git push origin <branch-name>
Pull changes from a remote repository:

bash
Copy code
git pull origin <branch-name>
12. Deleting Branches
Delete a branch locally:

bash
Copy code
git branch -d <branch-name>
Delete a branch remotely:

bash
Copy code
git push origin --delete <branch-name>
13. Undoing Changes
Restore a file to its last committed state:

bash
Copy code
git restore <filename>
Reset all changes in the working directory:

bash
Copy code
git reset --hard
vbnet
Copy code

Let me know if you need additional commands or sections added!




You said:
configuration is in the first position
ChatGPT said:
ChatGPT
Here’s the updated commands.md file with Configuration moved to the first position:

markdown
Copy code
# Git Commands Cheat Sheet

## 1. Configuration
- **Set global user email:**
  ```bash
  git config --global user.email "youremail@example.com"
Set global user name:
bash
Copy code
git config --global user.name "Your Name"
2. Repository Setup
Initialize a Git repository:

bash
Copy code
git init
Clone a repository:

bash
Copy code
git clone <repository-url>
3. Checking Status
Check the status of your working directory:
bash
Copy code
git status
4. Staging and Unstaging
Add a file to the staging area:

bash
Copy code
git add <filename>
Add all files to the staging area:

bash
Copy code
git add .
Unstage a file:

bash
Copy code
git restore --staged <filename>
5. Committing Changes
Commit staged changes:
bash
Copy code
git commit -m "commit message"
6. Branching
List all branches:

bash
Copy code
git branch
Create a new branch:

bash
Copy code
git checkout -b <branch-name>
Switch to another branch:

bash
Copy code
git checkout <branch-name>
7. Merging
Merge a branch into the current branch:
bash
Copy code
git merge <branch-name>
8. Viewing History
Show commit history:

bash
Copy code
git log
Show condensed commit history:

bash
Copy code
git log --oneline
9. Deleting Files
Delete a file:
bash
Copy code
rm <filename>
git rm <filename>
10. Viewing Remote Repositories
View remote repositories:
bash
Copy code
git remote -v
11. Push and Pull
Push changes to a remote repository:

bash
Copy code
git push origin <branch-name>
Pull changes from a remote repository:

bash
Copy code
git pull origin <branch-name>
12. Deleting Branches
Delete a branch locally:

bash
Copy code
git branch -d <branch-name>
Delete a branch remotely:

bash
Copy code
git push origin --delete <branch-name>
13. Undoing Changes
Restore a file to its last committed state:

bash
Copy code
git restore <filename>
Reset all changes in the working directory:

bash
Copy code
git reset --hard
sql
Copy code
