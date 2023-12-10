# Git Commands:

## Initialization:
- `git init`: Initialize a new Git repository.

## Cloning:
- `git clone <repository_url>`: Clone a repository from a remote URL.

## Status:
- `git status`: Show the status of changes as untracked, modified, or staged.

## Adding Changes:
- `git add <file>`: Add changes in a file to the staging area.
- `git add .` or `git add --all`: Add all changes to the staging area.

## Committing:
- `git commit -m "Commit message"`: Commit staged changes with a descriptive message.

## Branching:
- `git branch`: List all branches in the repository.
- `git branch <branch_name>`: Create a new branch.
- `git checkout <branch_name>`: Switch to a different branch.
- `git merge <branch_name>`: Merge changes from one branch into another.

## Remote Repositories:
- `git remote add origin <repository_url>`: Add a remote repository.
- `git push -u origin <branch_name>`: Push changes to a remote repository.
- `git pull origin <branch_name>`: Pull changes from a remote repository.

## Log:
- `git log`: Display a log of commits.

## Undoing Changes:
- `git reset <file>`: Unstage changes.
- `git reset --hard <commit_hash>`: Reset to a specific commit, discarding changes.
- `git revert <commit_hash>`: Create a new commit that undoes a previous commit.

# GitHub Commands:

## Repository Interaction:
- `git remote -v`: View remote repositories.
- `git remote add origin <repository_url>`: Add a remote repository.
- `git remote remove origin`: Remove a remote repository.

## Pull Requests:
- `git pull-request`: Open a pull request on GitHub.

## Forking:
- `git fork`: Fork a repository on GitHub.

## Collaboration:
- `git clone <forked_repository_url>`: Clone a forked repository.
- `git remote add upstream <original_repository_url>`: Add the original repository as an upstream remote.
- `git fetch upstream`: Fetch changes from the original repository.
- `git merge upstream/main`: Merge changes from the original repository into your local branch.

## GitHub Pages:
- `git checkout -b gh-pages`: Create a branch for GitHub Pages.
- Push HTML, CSS, or other web assets to this branch for hosting.
