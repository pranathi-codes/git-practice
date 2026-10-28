
# The Commit Cycle

## 1. What is a Commit?
A **commit** is a snapshot of your project at a specific point in time. It saves your changes and maintains the history of your project.

## 2. Essential Git Commands

| Command | Purpose |
|---|---|
| `git status` | Checks the current state of files |
| `git diff` | Shows line-by-line changes |
| `git add filename` | Stages a specific file |
| `git add .` | Stages all changes |
| `git commit -m "message"` | Saves staged changes as a commit |
| `git log` | Displays complete commit history |
| `git log --oneline` | Displays a short commit history |

## 3. The Commit Workflow

Follow these steps whenever you make changes to your project:

```bash
# 1. Check the file status
git status

# 2. Review the changes
git diff

# 3. Stage the changes
git add .

# 4. Commit the changes
git commit -m "Add meaningful message"

# 5. Verify the commit history
git log --oneline
```

## 4. Remember the Difference

- `git add` → Stages changes.
- `git commit` → Saves staged changes.
- `git log` → Shows commit history.
- `git diff` → Shows the exact differences.

## 5. Quick Revision

**Commit Cycle:**

`STATUS → DIFF → ADD → COMMIT → LOG`

---

**Conclusion:** Understand how to track changes, stage files, save commits, and review project history using Git.
