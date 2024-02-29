# Git Commands

Here are some useful Git commands for version control:

### Configuration

- `git config --global user.name "Your Name"`: Set your username globally.
- `git config --global user.email "your_email@example.com"`: Set your email globally.
- `git config --list`: List all the settings Git can find.

### Initialization

- `git init`: Initialize a new Git repository locally.
- `git clone <repository_url>`: Clone a repository from a URL.

### Basic Commands

- `git add <file_name>`: Add a specific file to the staging area.
- `git add .` or `git add --all`: Add all changes to the staging area.
- `git commit -m "Commit message"`: Commit changes with a message.
- `git status`: Check the status of the working directory and staging area.
- `git diff`: Show changes between commits, commit and working tree, etc.

### Branching and Merging

- `git branch`: List all the branches in the repository.
- `git branch <branch_name>`: Create a new branch.
- `git checkout <branch_name>`: Switch to a specific branch.
- `git merge <branch_name>`: Merge a branch into the current branch.
- `git branch -d <branch_name>`: Delete a branch.

### Remote Repository

- `git remote add <remote_name> <remote_url>`: Add a new remote repository.
- `git remote -v`: List all remote repositories.
- `git pull <remote_name> <branch_name>`: Fetch changes from a remote repository and merge.
- `git push <remote_name> <branch_name>`: Push changes to a remote repository.
- `git push -u <remote_name> <branch_name>`: Push changes and set the upstream branch.

### Undoing Changes

- `git reset <file_name>`: Unstage a file while retaining the changes.
- `git reset --hard`: Discard all changes in the working directory and staging area.
- `git revert <commit_hash>`: Revert a commit by creating a new commit.

### History

- `git log`: Display commit history.
- `git log --oneline`: Compact commit history.
- `git log --graph --decorate --oneline`: Graphical commit history.
- `git reflog`: Show a log of changes to the repository's HEAD.

### Miscellaneous

- `git stash`: Stash changes in a dirty working directory.
- `git stash apply`: Apply stashed changes to the working directory.
- `git clean -n`: Dry run to show which files will be removed with `git clean -f`.
- `git help`: Get help on any Git command.

### If you find this repository helpful, please consider giving it a star.
