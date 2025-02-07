# Git and GitHub Introduction

## Getting Started with Git
I started studying the basics of Git and how Git works. In Git, there are four areas where code is stored:
1. **Local Working Directory**
2. **Staging Area**
3. **Local Repository**
4. **Remote Repository**

There are a few commands to move the code from one area to another. I went step by step to understand each area and how to finally push our code to the remote repository.

### Understanding Git Areas
1. **Local Working Directory**: The directory where we are currently working and making changes to our code.
2. **Staging Area**: When we run the command `git add`, the code moves to the staging area, where snapshots of files are taken.
3. **Local Repository**: Running `git commit` moves the code to the local repository. Each commit requires a message to reflect the changes.
4. **Remote Repository**: Running `git push` uploads the changes to the remote repository. We also specify the branch to push the changes to.

## Difference Between Git and GitHub
- **Git**: Installed on a local machine and used for version control.
- **GitHub**: A cloud-based service that provides servers to create and manage repositories remotely.

## Concept of Branches
Branches allow multiple teams to work asynchronously on the same project by introducing changes separately.

## Common Git Commands
1. `git add` - Adds files to the staging area.
2. `git status` - Checks the status of the current branch.
3. `git commit -m "message"` - Finalizes changes in the local repository.
4. `git push origin <branch>` - Pushes changes to the remote repository.
5. `git merge <branch>` - Merges a branch into the main branch while keeping the full history.
6. `git rebase <branch>` - Merges branches by aligning commits linearly for a cleaner commit history.
7. `git squash` - Merges a branch into the main branch but combines all commits into a single commit for a cleaner history.
8. `git clone <repo_url>` - Clones a repository to the local machine.
9. `git reset <commit>` - Resets committed or staged changes.

## Pull Requests
Pull requests are raised when we fork a repository, make changes, and request the repository owner to merge them.

This is a brief introduction to Git and GitHub.
