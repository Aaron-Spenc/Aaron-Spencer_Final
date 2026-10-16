# Git Cheat Sheet - not extensive

### Quick Reference & Verification

#### Daily Git Commands
* `git clone <url>` - Downloads a repository to your computer
* `git pull` - Fetches and merges the latest changes from GitHub
* `git checkout -b <branch-name>` - Creates and switches to a new branch
* `git branch -m <new-branch-name>` - Renames your current active branch
* `git status` - Shows modified files and current branch status
* `git add <file>` - Stages changes to prepare them for a commit
* `git add .` - Stages all new and modified files in the current directory and its subdirectories
* `git add --all` - Stages all changes (new, modified, and deleted files) across the entire repository
* `git commit -m "message"` - Saves a snapshot of your staged changes
* `git push origin <branch-name>` - Uploads your local branch to GitHub

#### Command Flow Example (EXAMPLE ONLY)
> <br>
> ### Git Commands Practice
> 
> * `git clone https://github.com/HannahBorreson/software-systems-110.git` - Student downloads a repository to their computer
> * `git checkout -b borresonh_github_intro` - Student creates and switches to a new branch locally
> * `git branch -m github_intro` - Student decides to rename their current active branch
> 
> -- *Student edits the "Student Sign-off" section of README.md for assignment.* --
> 
> * `git add --all` - Student stages all changes across the entire repository
> * `git commit -m "Completed sign off"` - Student saves a snapshot of their staged changes with a usable message
> * `git push origin github_intro` - Student uploads their local branch to GitHub, a new branch is created remotely
> 
> -- *Student can now find their changes in the "github_intro" branch of their repository.* --
> -- *Students can update their dev or main branch with a Pull Request in GitHub* --
>
> <br>
>