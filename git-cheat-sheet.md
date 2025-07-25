# Git Interview Cheat Sheet

| **#** | **Question** | **Answer (Simple)** |
|-------|--------------|----------------------|
| 1 | What is Git? | A version control system to track file changes and collaborate with teams. |
| 2 | What is a repository? | A folder that stores project files and their change history. |
| 3 | What is a local repository? | Your personal copy of the repo on your computer. |
| 4 | What is a remote repository? | A repo stored on a server (e.g., GitHub, GitLab) for team collaboration. |
| 5 | Difference between local & remote repo? | Local → on your PC (offline work); Remote → on a server (team sharing & backup). |
| 6 | How to create a local repo? | `git init` |
| 7 | How to link local to remote? | `git remote add origin <repo-url>` |
| 8 | How to clone a repo? | `git clone <repo-url>` (copies remote to local) |
| 9 | What is an SSH key? | A secure way to connect to Git servers without typing a password. |
| 10 | What is version control? | A system to track and restore file changes anytime. |
| 11 | Why is Git important for web dev? | Tracks code changes, supports teamwork, and allows safe rollback. |
| 12 | How does Git help teamwork? | Multiple developers can work together and merge changes safely. |
| 13 | Basic Git commands? | `git init`, `git add`, `git commit`, `git push`, `git pull`, `git status` |
| 14 | What does `git status` do? | Shows staged, unstaged, and untracked files. |
| 15 | What does `git add` do? | Moves changes to the staging area for commit. |
| 16 | How to commit changes? | `git add .` → `git commit -m "message"` |
| 17 | What is committing? | Saving a snapshot of your project at a point in time. |
| 18 | How to see commit history? | `git log` |
| 19 | What is branching? | Creating a separate line of development for features or fixes. |
| 20 | Why switch branches? | To work separately on features/fixes without affecting main code. |
| 21 | How to switch branches? | `git checkout <branch>` or `git switch <branch>` |
| 22 | Difference: checkout vs switch? | `checkout` → switches branches & restores files; `switch` → only switches branches (simpler). |
| 23 | How to create a branch? | `git checkout -b <branch>` or `git switch -c <branch>` |
| 24 | What is Git fetch? | Downloads updates from remote repo without merging. |
| 25 | How to use fetch? | `git fetch <remote-name>` |
| 26 | What is Git pull? | Fetches and merges updates into your branch. |
| 27 | Difference: fetch vs pull? | `fetch` → only downloads; `pull` → downloads & merges. |
| 28 | Why is Git fetch useful? | Lets you review changes before merging. |
| 29 | Advantages of Git pull? | Quickly updates local repo and merges changes. |
| 30 | Difference: `git fetch origin` vs `git fetch .`? | `origin` → remote server; `.` → local repo (rarely used). |
| 31 | Why push changes? How to push? | To share updates with team → `git push <remote> <branch>` |
