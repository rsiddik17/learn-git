# **Learn Git**

# Initialize a new Git repository: 
- git init

# Clone a repository from GitHub:
- git clone https://github.com/username/repo-name.git

# Stage changes for commit:
- git add file.txt
- git add .  # Stage all changes

# Commit staged changes:
- git commit -m "Add initial project files"

# Push commits to remote repository:
- git push -u origin main

# Fetch and merge changes from remote repository:
- git pull origin main

# Branch Operations
List branches: git branch
Create a new branch: git branch <name>
Switch to a branch: git checkout <branch>
Merge a branch into the current branch: git merge <branch>

- git branch feature-login
- git checkout feature-login
# Make changes
- git add .
- git commit -m "Implement login functionality"
- git checkout main
- git merge feature-login