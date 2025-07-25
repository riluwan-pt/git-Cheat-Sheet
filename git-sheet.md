
# Git Questions & Answers (Simplified)

## 1. How does `git fetch` differ from `git pull`?
- **git fetch** → Downloads changes from remote but **does not merge**.
- **git pull** → Downloads and **merges** changes into the current branch.

## 2. Why is `git fetch` useful?
- Lets you **see remote changes** without changing your local code.
- Helps track collaborators' work before merging.

## 3. How do you switch branches in Git?
```bash
git checkout <branch-name>
# or
git switch <branch-name>
```
Switching branches lets you work on a different feature or fix.

## 4. What is a remote repository in Git?
A repository hosted on a **server** (like **GitHub** or **Bitbucket**) for collaboration and sharing.

## 5. How do you link a local repo to a remote repo?
```bash
git remote add origin <remote-url>
```
Links your local repo with a remote server.

## 6. What is Git?
Git is a **version control system** to track file changes and manage project history with team collaboration.

## 7. Why is Git important for web development?
- Tracks changes to code
- Allows team collaboration
- Easily rollback to previous versions

## 8. What is a repository in Git?
A folder containing **all project files** and their **change history**.

## 9. What is a local repository?
Your **personal workspace** on your computer containing project files and history.

## 10. How do you create a local repository?
```bash
git init
```
Initializes a Git repository in your folder.

## 11. Basic Git commands:
- `git init` → Initialize repo
- `git add` → Stage changes
- `git commit` → Save changes
- `git push` → Send changes to remote
- `git pull` → Fetch & merge changes

## 12. What is version control?
A system to **record file changes** and **restore previous versions** anytime.

## 13. How does Git help teamwork?
Multiple developers can **work together** and **merge changes** without overwriting each other’s work.

## 14. What is `git status`?
Shows the status of files: **staged**, **unstaged**, or **untracked**.

## 15. What does `git add` do?
Moves file changes to the **staging area** (ready to commit).

## 16. When to use `git restore`?
To **discard changes** and restore files to their last committed state.

## 17. What does committing mean?
Saving a **snapshot** of your project.

## 18. How to view commit history?
```bash
git log
```
Shows a list of commits with details.

## 19. What is branching in Git?
Creating a **separate line of work** for features or fixes without affecting main code.

## 20. Purpose of switching branches?
To **work on features/fixes separately** and keep the main code safe.

## 21. How to commit changes?
```bash
git add <file-name>   # stage files
git commit -m "message"
```

## 22. How to create a new branch?
```bash
git checkout -b <branch-name>
```
Creates and switches to the new branch.

## 23. Advantages of local & remote repos:
1. **Local repo** → Work offline & view history fast  
2. **Remote repo** → Collaboration & backup  
3. Together → Robust version control  

## 24. What is `git clone`?
Copies a remote repository to your local machine:
```bash
git clone <repo-url>
```

## 25. What is an SSH Key?
A **secure way** to connect to Git servers without typing a password.

## 26. Why push changes? How to push?
**Why:** Share updates with the team.  
**How:**  
```bash
git push <remote-name> <branch-name>
```

## 27. What is `git fetch`?
Downloads updates from remote **without merging**.

## 28. How to use `git fetch`?
```bash
git fetch <remote-name>
```

## 29. Advantages of `git pull`:
- Updates local repo quickly  
- Automatically merges changes  
- Keeps everyone up to date

## 30. Difference: `git fetch origin` vs `git fetch .`
- `git fetch origin` → Gets updates from remote repo (like GitHub).  
- `git fetch .` → Gets updates from your **own local repo** (rare advanced use).
