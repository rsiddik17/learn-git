# Git Learning Playground 🏗️

This repository contains a roadmap for learning Git step by step, from basics to advanced.  
It can be used as a personal note or a quick reference (cheatsheet).

---

## 1. Git Basics (Must Master First)

**Initialize a repository**
- git init
- git clone <url>

**Check status & logs**
- git status
- git log
- git log --oneline --graph

**Add & save changes**
- git add .        # all files
- git add <file>   # specific file
- git commit -m "message"

**View differences**
- git diff
- git diff --staged

**Config**
- git config --global user.name "Your Name"
- git config --global user.email "you@example.com"

**Undo simple changes**
- git restore <file>
- git reset <file>

## 2. Remote Repository

**Add a remote**
- git remote add origin <url>
- git remote -v

**Push to remote**
- git branch -M main
- git push -u origin main
- git push

**Pull & fetch**
- git pull
- git fetch
- git pull origin main

## 3. Branching Workflow

**Create & switch branches**
- git branch
- git checkout -b feature-x
- git switch -c feature-x
- git switch main

**Merge a branch**
- git merge feature-x

**Delete / rename branch**
- git branch -d feature-x
- git branch -m new-name

**Delete a branch on remote**
- git push origin --delete <branch>

**View all branches**
- git branch -r
- git branch -a

## 4. Undo & Revise Commits

**Amend the last commit**
- git commit --amend

**Revert a commit**
- git revert <commit_hash>

**Use reset (be careful)**
- git reset <file>
- git reset --hard <commit_hash>

## 5. Advanced Staging & Stash

**Stage part of a file**
- git add -p

**Temporarily save changes**
- git stash
- git stash pop

## 6. Advanced Collaboration

**Safe force push**
- git push --force-with-lease

**Show changes since a commit**
- git diff <commit_hash>

## 7. Tagging & Release

**Create a version tag**
- git tag v1.0.0
- git push origin v1.0.0

## 8. Advanced Workflow

**Cherry-pick a commit**
- git cherry-pick <commit_hash>

**Rebase (linear merge)**
- git rebase main

**Clean untracked files**
- git clean -f