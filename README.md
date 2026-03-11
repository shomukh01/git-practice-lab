# My Git & GitHub Learning Experience

A practical repository demonstrating my understanding of Git version control and GitHub collaboration.

---

## 📖 Overview
This project represents my hands-on practice in learning Git and GitHub.  
I applied version control concepts, tracked file changes, and understood how developers manage and collaborate on software projects.

---

## ⚙️ Basic Git Commands

### Initialize Repository
`git init` → Create a new local repository.

### Check Status
`git status` → View file states (tracked / untracked).

### Stage Files
`git add .` → Move files to the staging area.

### Commit Changes
`git commit -m "message"` → Save a snapshot of the project.

### View History
`git log` → Detailed commit history.  
`git log --oneline` → Simplified history.

---

## 🌿 Branching

`git branch` → Create or list branches.  
`git checkout <branch>` or `git switch <branch>` → Switch branches.

### Merge Branches
`git merge <branch>` → Combine branches.

### Merge Types
- **Fast-Forward Merge** → Branch pointer moves forward without creating a new commit.
- **Normal Merge** → Creates a new merge commit.

---

## 🔁 Undo & History Management

### Amend Commit
`git commit --amend` → Modify the last commit.

### Reset
`git reset <commit>` → Move to a previous commit.

| Type | Result |
|------|--------|
| Soft | Keeps staged changes |
| Mixed | Keeps changes in working directory |
| Hard | Deletes all changes |

### Safe Undo
`git revert <commit>` → Creates a new commit that cancels previous changes.

### Recover Lost Commits
`git reflog` → Shows HEAD movements and helps recover commits after hard reset.

---

## 🧩 Advanced Commands

### Cherry-pick
`git cherry-pick <commit-id>`  
Apply a specific commit from another branch.

### Rebase
`git rebase <branch>`  
Reapply commits on top of another branch to keep history linear.

---

## 🌐 Remote Repository (GitHub)

`git remote add origin <repo-link>` → Connect local repo to GitHub.  
`git push -u origin main` → Upload commits.  
`git pull` → Download updates.

---

## 🚫 Using .gitignore

Used to ignore unnecessary files.

Example:
*.out
*.o
*.exe

---

## 🧹 Repository State

- **Clean Repository** → All changes committed.  
- **Dirty Repository** → Modified or untracked files exist.

Command used: `git status`

---

## 🧠 Git Concepts Learned

- Repository  
- Working Directory  
- Staging Area  
- Commit  
- Branch  
- Merge  
- Merge Conflict  
- HEAD  
- Tracked vs Untracked Files  
- Local vs Remote Repository  

---

## 📊 Repository Visualization

`git log --oneline --graph --all`  
Used to visualize branch structure and commit relationships.

---

## 🤝 GitHub Experience

Through this project, I learned how to:

- Create **Public and Private repositories**
- Share projects online
- Explore open-source communities
- Use **Fork** to copy repositories
- Use **Pull Requests** for collaboration
- Review project history
- Accept feedback from developers

---

## 🔄 Git Workflow

1. Modify files  
2. Check status  
3. Stage changes  
4. Commit  
5. Push updates  

---

## 🎯 Skills Gained

- Understanding version control systems  
- Managing project history  
- Working with branches and merges  
- Solving merge conflicts  
- Recovering lost commits  
- Sharing and collaborating on GitHub  

---

## ✅ Conclusion

This repository provided practical experience with Git and GitHub.  
It improved my ability to manage code versions, recover from mistakes, and collaborate effectively using modern development workflows.