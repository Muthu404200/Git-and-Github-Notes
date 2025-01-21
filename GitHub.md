## What is Git?
Git is a distributed version control system that allows developers to:
- Track changes in code.
- Collaborate on projects.
- Manage multiple versions of a project.
- Work offline with a full local repository.

---

## Basic Git Workflow
1. **Working Directory**: Where you make changes to files.
2. **Staging Area**: Prepare changes for a commit.
3. **Local Repository**: Stores committed changes.
4. **Remote Repository**: Backup and share code (e.g., GitHub).

---

## Common Git Commands

### Setup
- Set username: `git config --global user.name "Your Name"`
- Set email: `git config --global user.email "your.email@example.com"`
- Default branch to `main`: `git config --global init.defaultBranch main`

### Initializing & Cloning
- Initialize a repository: `git init`
- Clone a repository: `git clone <repo_url>`

### Adding & Committing
- Check status: `git status`
- Add files to staging: `git add .` (or specific file: `git add filename`)
- Commit changes: `git commit -m "Commit message"`

### Working with Remote Repositories
- Add a remote: `git remote add origin <repo_url>`
- Push changes: `git push -u origin main`
- Pull changes: `git pull origin main`

### Branching & Merging
- Create a branch: `git checkout -b branch-name`
- Switch branches: `git checkout branch-name`
- Merge branch: `git merge branch-name`
- Delete branch:
  - Locally: `git branch -d branch-name`
  - Remotely: `git push origin --delete branch-name`

- Rollback changes:
  - Soft reset: `git reset <commit_hash>` (keeps changes in working directory)
  - Hard reset: `git reset --hard <commit_hash>` (removes changes)


