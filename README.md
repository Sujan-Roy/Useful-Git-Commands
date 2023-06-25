# Useful-Git-Commands

# Getting & Creating Projects on Githunb

| Command | Description |
| --- | --- |
| git init | Initialize a local git repository |
| git clone ssh://git@github.com/[username]/[repository-name].git | Create a local copy of a remote repository |

# Basic Command
| Command | Description |
| --- | --- |
|git status | Check status |
| git add [file-name.txt] | Add a file to the current repository area |
|git add . | Add all new and changed files to the current repository area |
| git commit -m "[commit message]" | Commit changes |
|git rm -r [file-name.txt]| Remove a file (or folder) |

# Branching Command
| Command | Description |
| --- | --- |
| git branch |  List branches (The asterisk (*) indicates the current branch) |
| git branch -a | List all branches (local and remote)  |
| git branch [branch name] |  Create a new branch |
| git branch -d [branch name] |  	Delete a branch |
| git push origin --delete [branch name] |	Delete a remote branch    |
| git checkout -b [branch name]	| Create a new branch on the current repository   |
| git checkout -b [branch name] origin/[branch name]	| Clone a remote branch and switch to it   |
|  git branch -m [old branch name] [new branch name]	| Rename a local branch   |
| git checkout [branch name]	| Switch to a branch  |
|  git checkout -	| Switch to the branch last checked out   |
|  git checkout -- [file-name.txt]	| Discard changes to a file   |

# Merging Command
| Command | Description |
| --- | --- |
|  git merge [branch name]	| Merge a branch into the active branch   |
|  git merge [source branch] [target branch]	| Merge a branch into a target branch  |
| git stash	| Stash changes in a dirty working directory   |
|  git stash clear	| Remove all stashed entries   |
# Inspection & Comparison Command
| Command | Description |
| --- | --- |
| git log	| View changes   |
|  git log --summary	| View changes (detailed)   |
| git log --oneline	| View changes (briefly)   |
| git diff [source branch] [target branch]	| Preview changes before merging   |


