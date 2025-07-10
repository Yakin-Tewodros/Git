# GIT

## Basic Terminologies

- 'Repository' is the project folder that tracks the changes for all the code of the project we work on.
- 'Untracked file' is one that has not been added to the staging area.
- 'Tracked file' is one that is in the staging area.
- 'Staging area' is the safekeeping place before files are commited. Files in the staging area will be tracked.
- 'Commiting changes' is used to track the current state of the changes of the tracked files.
- 'Branch' is a copy of the document so we dont mess up the original.
- 'Pull request' is a proposal to merge a set of changes from one branch into another.
- 'Merge' is applying the changes of one branch on another one.
- 'The GitHub Flow':
  - Clone a repository, checkout a new branch, make your changes, git add, git commit, git push, open a pull request, merge PR and delete branch.

## Basic Commands

- `git status` shows files added, deleted or modified in the working directory.
- `git add [file_name | '.' for all files in the folder]` adds files to the staging area. [Should be done after finishing work in the file](https://youtu.be/rE2zRhZdjFU?list=PL0lo9MOBetEFcp4SCWinBdpml9B2U25-f&t=264)
- `git commit -m "commit message"` this along with `git add` helps track changes and store them.
- `git clone` is used to get a local copy of a repository.
- `git checkout -b [update_name]` creates a new branch and switches to it.
- `git branch` lists branches in a repo.
- `git switch [branch_name]` switches to the specified branch.
- `git push [remote] [branch_name]` uploads the local changes to the remote repository.
- `git pull` returns changes that were made on the remote repository.
- `git show` shows changes made (the diff) and other data of the branch we're on.
- `git branch -d [update_name]` deletes the branch on the local repository
- `git push --delete [remote] [update_name]` deletes the branch in the remote repository

## Notes

- Obviously renaming something doesn't automatically add it.
