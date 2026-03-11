# Git and GitHub Practice

A practical repository demonstrating my understanding of Git version control and GitHub collaboration.

---

## 📌 Contents
- Overview  
- Git Commands  
- Advanced Commands  
- Remote Repository  
- Using .gitignore  
- Repository State  
- Git Concepts  
- Project History  
- GitHub Experience  
- Workflow  
- Skills  
- Conclusion  

---

## 📖 Overview
This project represents my hands-on practice in learning Git and GitHub.  
I applied version control concepts, tracked file changes, and understood how developers manage and collaborate on software projects.

---

## ⚙️ Git Commands

### Initialize Repository  
`git init` → create a new local repository.

### Check Status  
`git status` → view file states.

### Stage Files  
`git add .` → move files to staging.

### Commit Changes  
`git commit -m "message"` → save project snapshot.

### Amend Commit  
`git commit --amend` → update the last commit.

### Undo Changes  
`git reset` → move back to a previous commit.  
Soft → keep staged changes  
Mixed → keep changes in working directory  
Hard → remove all changes  

### Safe Undo  
`git revert` → create a new commit that cancels previous changes.

### View History  
`git log` → detailed history  
`git log --oneline` → simplified history

### Branching  
`git branch` → create/list branches  
`git checkout <branch>` or `git switch <branch>` → switch branches

### Merge  
`git merge <branch>` → combine branches

### Temporary Save  
`git stash` → save changes temporarily

### Restore  
`git restore <file>` → discard changes

---

## 🔧 Advanced Commands

### Cherry-pick  
`git cherry-pick <commit-id>`  
Apply a specific commit from another branch.

### Rebase  
`git rebase <branch>`  
Reapply commits on top of another branch to keep history linear.

---

## 🌐 Remote Repository

`git remote add origin <repo-link>` → connect to GitHub  
`git push -u origin main` → upload commits  
`git pull` → download updates  

---

## 🚫 Using .gitignore
Used to ignore unnecessary files.

Example:
*.out  
*.o  
*.exe  

---

## 🧹 Repository State

A **clean repository** means all changes are committed.  
A **dirty repository** means there are untracked or modified files.

Command used:
`git status`

---

## 🧠 Git Concepts
- Repository  
- Working Directory  
- Staging Area  
- Commit  
- Branch  
- Merge  
- Merge Conflict  
- Tracked vs Untracked Files  
- HEAD  
- Local vs Remote Repository  

---

## 🕒 Project History
Git tracks project versions through commits.

Commands:
`git log`  
`git log --oneline`

This helps follow project updates and revert when needed.

---

## 🤝 GitHub Experience
Through this project, I learned how to:

- Create public and private repositories  
- Share projects online  
- Explore open-source projects  
- Use Fork to copy repositories  
- Use Pull Requests for collaboration  
- Accept feedback from developers  

---

## 🔄 Workflow
1. Modify files  
2. Check status  
3. Stage changes  
4. Commit  
5. Push updates  

---

## 🎯 Skills
- Understanding version control  
- Managing project history  
- Working with branches  
- Sharing code on GitHub  
- Learning from developer communities  

---

## ✅ Conclusion
This repository provided practical experience with Git and GitHub.  
It improved my ability to manage code versions and collaborate effectively.