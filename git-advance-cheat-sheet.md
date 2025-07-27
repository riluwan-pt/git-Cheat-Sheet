## Git Advance

### 1. What is the staging area in Git?

A place where you prepare your changes before saving them in Git (**committing**).

### 2. What is Git reset?

It moves your project back to an earlier version.

### 3. How does `git reset` differ from `git reset --hard`?

* `git reset`: **keeps** your changes.
* `git reset --hard`: **removes all** changes and files too.

### 4. What is Git revert?

It **undoes a commit** by creating a new one that cancels it out.

### 5. What is Git restore?

It brings files back to how they were before, **discarding** your recent changes.

### 6. How do you explore remote branches in Git?

Use:

```bash
git branch -r
git checkout <branch>
```

### 7. What does it mean to time travel to a commit in Git?

It means going back to an earlier version of your code.

### 8. How can you time travel to a commit in Git?

```bash
git checkout <commit-hash>
```

### 9. What is a detached HEAD state in Git?

You're not on a branch, just looking at an old version of your project.

### 10. What is `.gitignore` in Git?

A file that tells Git what to **ignore** (not track).

### 11. What types of files can go in `.gitignore`?

Examples:

```gitignore
*.log
nodemodule/
.env
```

### 12. What is "switching branches with unstaged changes"?

Changing branches even if your changes aren’t saved yet (**not committed**).

### 13. How can you switch branches with unstaged changes?

Options:

* Commit them
* Stash them (`git stash`)
* Or discard them

### 14. Why switch branches with unstaged changes?

To work on something else without losing your current work.

### 15. What does "move to a new branch with unstaged changes" mean?

You keep your current changes and switch to a new branch to continue working.

### 16. What is "reverting changes after the last commit"?

Undoing your last commit by creating a new one that cancels it.

### 17. How to revert the last commit?

```bash
git revert HEAD
```

### 18. How is `git revert` different from other undo commands?

* `git revert`: **adds** a new commit
* `git reset` / `git checkout`: **modify** history or files

### 19. Why amend the last commit?

To fix or add something to your last commit without making a new one.

### 20. How to amend the last commit?

```bash
git commit --amend
```

### 21. What is Git workflow?

The process of using Git — like **branching**, **committing**, and **pushing**.

### 22. What is a Pull Request (PR)?

A request to merge your branch into another, mainly on **GitHub**.

### 23. What is a Merge Request (MR)?

Same as PR, but on **GitLab** and similar platforms.

### 24. How does a PR help in Git workflow?

It lets others **review** your code before merging it.

### 25. What is a conflict in a Merge Request?

When two branches edit the **same code**, and Git can't decide which to keep.

### 26. How to resolve conflicts in a Merge Request?

* Open the file
* Edit to resolve
* Use:

```bash
git add <file>
git commit
```

### 27. What is Git rebase?

Moves your changes on top of another branch to make history clean.

### 28. How is `rebase` different from `merge`?

* `rebase`: rewrites history
* `merge`: keeps all history with a merge commit

### 29. Why use Git rebase?

To make the commit history **linear and clean**.

### 30. When to use Git rebase?

Before merging your branch to keep history neat.

### 31. What is Git stash?

Temporarily saves changes so you can work on something else.

### 32. How to stash changes?

```bash
git stash
```

### 33. How to get back stashed changes?

```bash
git stash apply  # keep stash
# or
git stash pop    # apply and remove
```

### 34. What is Git diff?

Shows differences between files, branches, or commits.

```bash
git diff
```

### 35. What is a Git tag?

A label for a commit, like a version number (e.g., `v1.0`).

### 36. Difference between deleting and renaming a branch?

* **Delete**: removes the branch.
* **Rename**: changes its name but keeps everything.

### 37. How to rename a branch?

```bash
git branch -m old_name new_name
```

### 38. When to use `git branch -D` instead of `-d`?

Use `-D` to **force delete** a branch, even if not merged.

### 39. What is merging branches?

Combining changes from one branch into another.

### 40. What is HEAD in Git?

**HEAD** points to your current commit or branch.
