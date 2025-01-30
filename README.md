
# Git Basics

Git is a distributed version control system used to track changes in source code during software development. It allows multiple developers to work on a project simultaneously without interfering with each other's work.

## Key Concepts

- **Repository (Repo)**: A directory where Git tracks changes to files.
- **Commit**: A snapshot of the repository at a specific point in time.
- **Branch**: A parallel version of the repository, allowing for independent development.
- **Merge**: Combining changes from different branches.
- **Clone**: Creating a copy of a remote repository on your local machine.
- **Pull**: Fetching changes from a remote repository and merging them into your local branch.
- **Push**: Uploading local repository changes to a remote repository.

## Basic Git Commands

### Initializing a Repository
```bash
git init
```
Initializes a new Git repository in the current directory.

Cloning a Repository
```bash
git clone <repository-url>
```
Creates a copy of a remote repository on your local machine.

Checking Status
```bash
git status
```
Shows the status of changes as untracked, modified, or staged.

Adding Files
```bash
git add <file-name>
```
Adds a file to the staging area. Use git add . to add all changes.

Committing Changes
```bash
git commit -m "Commit message"
```
Commits the staged changes with a descriptive message.

Viewing Commit History
```bash
git log
```
Displays the commit history of the repository.

Creating a Branch
```bash
git branch <branch-name>
```
Creates a new branch.

Switching Branches
```bash
git checkout <branch-name>
```
Switches to the specified branch.

Merging Branches
```bash
git merge <branch-name>
```
Merges the specified branch into the current branch.

Pushing Changes
```bash
git push origin <branch-name>
```
Uploads local branch changes to the remote repository.

Pulling Changes
```bash
git pull origin <branch-name>
```
Downloads changes from the remote repository and merges them into the current branch.

Viewing Remote Repositories
```bash
git remote -v
```
Lists the remote repositories associated with the local repository.

##Useful Tips


- Always pull the latest changes before starting work to avoid conflicts.

- Write clear and descriptive commit messages.

- Use branches to isolate new features or bug fixes.