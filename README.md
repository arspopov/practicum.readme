
# Git Basics - Commands Guide

Git is a powerful version control system used for tracking changes in source code. Below are some of the most commonly used Git commands for beginners.

## 1. Git Configuration
Before starting to use Git, you need to configure your identity.

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## 2. Initializing a Repository
To start a new Git repository, navigate to your project directory and run:

```bash
git init
```

## 3. Cloning a Repository
To clone an existing repository from a remote server:

```bash
git clone https://github.com/username/repo.git
```

## 4. Checking the Repository Status
To see the status of your working directory:

```bash
git status
```

## 5. Staging Files
To add specific files to the staging area:

```bash
git add filename
```

To add all files in the current directory:

```bash
git add .
```

## 6. Committing Changes
To commit your changes with a descriptive message:

```bash
git commit -m "Your commit message"
```

## 7. Viewing Commit History
To view the commit history in the repository:

```bash
git log
```

## 8. Pushing Changes
To push your changes to the remote repository:

```bash
git push origin branch-name
```

## 9. Pulling Changes
To pull the latest changes from the remote repository:

```bash
git pull origin branch-name
```

## 10. Creating a Branch
To create a new branch:

```bash
git checkout -b new-branch-name
```

## 11. Merging Branches
To merge a branch into the current branch:

```bash
git merge branch-name
```

## 12. Resolving Merge Conflicts
If you encounter a merge conflict, Git will pause the merge process. Resolve conflicts, then mark them as resolved with:

```bash
git add filename
git commit
```

## 13. Deleting a Branch
To delete a local branch:

```bash
git branch -d branch-name
```

To force delete a branch:

```bash
git branch -D branch-name
```

## 14. Undoing Changes
To revert unstaged changes:

```bash
git checkout -- filename
```

To reset all changes in the working directory:

```bash
git reset --hard
```

---

By mastering these commands, you'll have a strong foundation for using Git effectively in your projects.
