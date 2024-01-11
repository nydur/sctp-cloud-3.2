# 3.2 Introduction to GIT II Assignment

## What is GitHub Authentication?

A process to prove your identity when you access your account or the resources.

## What are the methods available to implement Github Authentication?

- 2FA / MFA
    - Github Mobile, Authenticator app(s), SMS, etc
- Passkeys
    - Bitwarden, Onepass, etc

---

## Common Github commands

`git version`

To verify Git is installed on local terminal

`git init`

Initialise a Git repository in current directory

`git clone <repository-url>`

Clones the repostory from remote to current directory

`git add <file>` or `git add .`

Add specific file to staging area or adds all files to staging area

`git status`

Show current state of the repository, showing if there are any changes to the files or if new files or branch is added

`git commit -m “<message>”`

Prepares a new commit for the modified file(s) in the staging area

`git push`

Pushes the update to the files to the repository

`git pull`

Retrieves any updates to the files in the repository to local directory

`git branch`

Checks the available branch in the repository

`git branch <new-branch-name`

Creates a new branch

`git branch -d <branch-name>`

Deletes the specific branch

`git checkout -b <new-branch-name>`

Creates and switch to the specific branch

`git checkout <numbers retrieve from commit history>` or `git main`

To review the past/previous state of the file

`git push --set-upstream origin <branch-name>`

Set the local terminal to prepare any future `git push` from the current branch

`git diff`

To review the changes made to the file before committing to `git push`

`git log`

To show the history of the commits made in the repository

`git merge <new-branch>`

Combines new branch to main branch