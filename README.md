git practice repo
this was added from the cloned local repo

## learned git commands:

* git init                            : start git-tracking on current folder
* git branch -M main                  : change current branch name to <main>, forcing if needed
* git remote add origin <repo_url>    : link to remote repo is in <origin>
* git fetch origin                    : download remote repo into origin
* git switch <branch_name>            : go to branch <branch_name>
* git merge origin/<branch_name>      : merge remote branch <origin/branch_name> into local branch <branch_name>
* git add                             : stage files
* git status                          : check current state of the local repo (staged/unstaged/untracked)
* git commit -m <message>             : commit 
* git log --oneline                   : show last commits
* git push                            : upload to remote repo 
* git clone <repo_url>                : clone (copy) remote repo into local folder
* git log --graph --decorate --oneline --all : show branch history as a nice graph