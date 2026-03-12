# My Git & GitHub Learning Experience

A practical repository demonstrating my understanding of Git version control and GitHub collaboration.

---

## 📑 Table of Contents

* [Overview](#overview)
* [Basic Git Commands](#basic-git-commands)
* [Branching](#branching)
* [Undo & History Management](#undo--history-management)
* [Cherry-pick Operation](#-cherry-pick-operation)
* [Revert Operation](#-revert-operation)
* [Advanced Commands](#advanced-commands)
* [Remote Repository](#remote-repository-github)
* [Using .gitignore](#using-gitignore)
* [Repository State](#repository-state)
* [Git Concepts Learned](#git-concepts-learned)
* [Repository Visualization](#repository-visualization)
* [GitHub Experience](#github-experience)
* [Git Workflow](#git-workflow)
* [Skills Gained](#skills-gained)
* [Conclusion](#conclusion)

---

## 📖 Overview

Conflict resolved
I applied version control concepts, tracked file changes, and understood how developers manage and collaborate on software projects.

---

## ⚙️ Basic Git Commands

* `git init` → Create a new local repository.
* `git status` → View file states.
* `git add .` → Stage files.
* `git commit -m "message"` → Save project snapshot.
* `git log` → View detailed history.
* `git log --oneline` → View simplified history.

---

## 🌿 Branching

* `git branch` → Create or list branches.
* `git checkout <branch>` / `git switch <branch>` → Switch branches.
* `git merge <branch>` → Merge branches.

### Merge Types

* **Fast-Forward Merge**
* **Normal Merge Commit**

---

## 🔁 Undo & History Management

* `git commit --amend` → Modify last commit.
* `git reset` → Move to previous commit.

| Type  | Effect                         |
| ----- | ------------------------------ |
| Soft  | Keep staged changes            |
| Mixed | Keep working directory changes |
| Hard  | Delete all changes             |

---

## 🧩 Cherry-pick Operation

`git cherry-pick <commit-id>` → Apply a specific commit from another branch without merging the full branch history.

### Purpose

* Reuse fixes
* Transfer selected features
* Keep history clean

---

## 🔄 Revert Operation

`git revert <commit-id>` → Create a new commit that safely cancels previous changes.

### Purpose

* Undo mistakes safely
* Preserve history
* Work safely in teams

---

## 🧩 Advanced Commands

* `git rebase <branch>` → Keep history linear.
* `git reflog` → Recover lost commits.

---

## 🌐 Remote Repository (GitHub)

* `git remote add origin <repo>`
* `git push -u origin main`
* `git pull`

---

## 🚫 Using .gitignore

Used to ignore unnecessary files.

```
*.out
*.o
*.exe
```

---

## 🧹 Repository State

* Clean → No pending changes
* Dirty → Modified or untracked files

Command: `git status`

---

## 🧠 Git Concepts Learned

Repository — Working Directory — Staging Area — Commit — Branch — Merge — Conflict — HEAD — Remote vs Local

---

## 📊 Repository Visualization

```
git log --oneline --graph --all
```

Used to understand branch structure.

---

## 🤝 GitHub Experience

* Creating repositories
* Forking projects
* Using Pull Requests
* Reviewing history
* Collaborating with developers

---

## 🔄 Git Workflow

1. Modify
2. Status
3. Add
4. Commit
5. Push

---

## 🎯 Skills Gained

* Version control understanding
* Branch management
* Conflict resolution
* History recovery
* Collaboration


## ✅ Conclusion

This project strengthened my practical understanding of Git and GitHub workflows and improved my ability to manage real development scenarios.

Rebase resolved