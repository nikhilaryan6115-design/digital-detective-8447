# Mission 6 — Git and GitHub

> **Student:** Nikhil Aryan | **USN:** 2392608447 | **Campus:** Bengaluru

## 1. Task / objective
Understand version control, stage and commit changes, create and publish a branch (`update-about`), open and merge a Pull Request on GitHub, and build a comprehensive Git command glossary.

## 2. Work completed
* Explored basic Git workflow operations (`status`, `add`, `commit`, `log`) and explained the difference between staging and committing.
* Created a dedicated branch named `update-about`, added a "My Learning" section to the root `README.md`, committed the change, and pushed the branch to GitHub.
* Opened a Pull Request from `update-about` into `main` on GitHub, reviewed the changes, merged the PR into `main`, and pulled the merged changes back locally.
* Constructed a complete Git command glossary covering repository initialization, inspection, staging, committing, branching, pushing, and pulling in `mission-06-git-github/notes.md`.

## 3. Commands / tools used
* `git status`: Checked working tree and staging area.
* `git add <file>`: Staged modified files.
* `git commit -m "..."`: Created version-controlled commits with descriptive messages.
* `git log --oneline`: Inspected chronological commit history.
* `git branch` / `git switch -c update-about`: Created and switched to the feature branch.
* `git push -u origin update-about`: Published branch to GitHub.
* `gh pr create` / GitHub Web UI: Opened Pull Request.
* `gh pr merge` / GitHub Web UI: Merged Pull Request into `main`.
* `git pull origin main`: Synchronized local workspace with merged remote repository.

## 4. My understanding
* **Staging vs. Committing:** Staging (`git add`) selectively prepares files for the next snapshot without writing them permanently, while committing (`git commit`) seals staged modifications into an immutable, version-controlled history checkpoint.
* **Branches and Pull Requests:** A branch provides an isolated environment to develop updates without endangering the stable codebase. A Pull Request facilitates peer review, collaboration, and discussion before integrating proposed changes into the primary branch.

## 5. Difficulties faced
No major difficulties.

## 6. How I resolved them
Not applicable.

## 7. Evidence / files
* `mission-06-git-github/notes.md` (Contains workflow table, staging vs. commit analysis, branch/PR explanations, and Git glossary)
* `mission-06-git-github/README.md`
* GitHub Pull Request and branch activity on `nikhilaryan6115-design/digital-detective-8447`

## 8. Commit details
* **Commit message:** `Complete Git and GitHub collaboration mission`
* Pushed to remote: `https://github.com/nikhilaryan6115-design/digital-detective-8447`
