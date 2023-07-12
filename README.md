# Git Commands

Below is a list of commonly used Git commands, along with their descriptions and uses.

| Command | Description | Usage |
|---------|-------------|-------|
| `git init` | Initializes a new Git repository in the current directory. | `git init` |
| `git clone` | Creates a copy of a remote repository on your local machine. | `git clone <repository URL>` |
| `git add` | Adds file(s) or changes to the staging area to be committed. | `git add <file(s)>` |
| `git commit` | Records the changes to the repository with a commit message. | `git commit -m "Commit message"` |
| `git push` | Uploads local repository changes to a remote repository. | `git push <remote> <branch>` |
| `git pull` | Downloads and integrates changes from a remote repository to the current branch. | `git pull <remote> <branch>` |
| `git branch` | Lists, creates, or deletes branches in the repository. | `git branch`, `git branch <branch>`, `git branch -d <branch>` |
| `git checkout` | Switches between branches or restores files from a specific commit. | `git checkout <branch/commit>`, `git checkout -- <file(s)>` |
| `git merge` | Combines changes from different branches into the current branch. | `git merge <branch>` |
| `git status` | Shows the current state of the repository, including modified files. | `git status` |
| `git log` | Displays a list of commits in reverse chronological order. | `git log` |
| `git remote` | Manages remote repositories linked to the local repository. | `git remote add <name> <URL>`, `git remote -v` |
| `git stash` | Temporarily saves changes that are not ready to be committed. | `git stash`, `git stash pop` |
| `git diff` | Shows the differences between files in the working directory and the repository. | `git diff`, `git diff <commit> <commit>`, `git diff --staged` |
| `git fetch` | Downloads changes from a remote repository without merging them. | `git fetch <remote>` |
| `git reset` | Unstages files or undoes changes to the repository. | `git reset <file(s)>`, `git reset <commit>` |
| `git revert` | Creates a new commit that undoes the changes made in a previous commit. | `git revert <commit>` |
| `git tag` | Marks a specific commit as a reference point with a meaningful name. | `git tag <tagname>`, `git tag -a <tagname> -m "Tag message"` |
| `git cherry-pick` | Applies the changes made in a specific commit to the current branch. | `git cherry-pick <commit>` |
| `git remote` | Manages remote repositories linked to the local repository. | `git remote add <name> <URL>`, `git remote -v` |
| `git rebase` | Incorporates changes from one branch onto another. | `git rebase <branch>` |
| `git show` | Displays the details and changes of a specific commit. | `git show <commit>` |
| `git config` | Sets configuration values for your Git environment. | `git config --global user.name "Your Name"`, `git config --global user.email "youremail@example.com"` |

Feel free to refer to the official Git documentation for more detailed explanations and additional commands.
