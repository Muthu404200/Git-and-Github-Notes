# Git and GitHub Notes

## Git Notes

### What is Git?
Git is a distributed version control system used to track changes in source code during software development. It allows multiple people to collaborate on projects without interfering with each other's work.

### Basic Git Commands

1. **`git init`**  
   Initializes a new Git repository in the current directory.

2. **`git clone <repository>`**  
   Clones an existing repository from a remote location (e.g., GitHub) to your local machine.

3. **`git status`**  
   Shows the current state of the working directory (which files have been modified, added, or deleted).

4. **`git add <file>`**  
   Stages changes (file(s)) for commit. Use `git add .` to stage all modified files.

5. **`git commit -m "message"`**  
   Commits the staged changes with a descriptive message.

6. **`git push`**  
   Pushes the local commits to the remote repository (e.g., on GitHub).

7. **`git pull`**  
   Fetches the changes from the remote repository and merges them into the current branch.

8. **`git branch`**  
   Lists all branches in your repo. You can create a new branch with `git branch <branch_name>`.

9. **`git checkout <branch_name>`**  
   Switches to a different branch.

10. **`git merge <branch_name>`**  
    Merges changes from another branch into the current branch.

11. **`git log`**  
    Displays the commit history.

12. **`git diff`**  
    Shows the differences between the working directory and the staging area, or between commits.

13. **`git reset`**  
    Unstages a file or resets the repository to a previous commit.

---

## GitHub Notes

### What is GitHub?
GitHub is a cloud-based platform that hosts Git repositories, enabling collaboration among developers. It adds features like pull requests, issues, and more.

### Basic GitHub Concepts

1. **Repository**  
   A GitHub repository (or "repo") is where your project’s files are stored. It's essentially a place to hold all your code, documentation, and configuration files.

2. **Fork**  
   A copy of someone else's repository on your own GitHub account. This allows you to freely make changes without affecting the original project.

3. **Pull Request (PR)**  
   A way to propose changes to a project. After you make changes in a forked repo, you can submit a pull request to ask for the changes to be merged into the original repo.

4. **Issues**  
   A GitHub feature used to track bugs, enhancements, tasks, or other feedback in a project.

5. **Actions**  
   GitHub Actions are used to automate workflows for continuous integration (CI), deployment (CD), and other tasks.

6. **Branches on GitHub**  
   GitHub repositories usually have a `main` or `master` branch. Developers often create separate branches for features or bug fixes.

7. **GitHub Pages**  
   A feature that lets you turn your repository into a static website (great for portfolios or documentation).

8. **Collaborators**  
   People who are invited to work on a repository. On a public repo, anyone can fork it, but only collaborators can push changes directly.

---

## Workflow Example (Git + GitHub)

1. **Clone the repository:**
   ```bash
   git clone https://github.com/username/repo.git
