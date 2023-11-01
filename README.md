## Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [GIT](#git)
  - [Basic Commands](#basic-commands)
  - [Intermediate Commands](#intermediate-commands)
  - [Advanced Commands](#advanced-commands)
  - [GitHub](#github)
  - [GitLab](#gitlab)
- [Markdown](#markdown)
- [Bibliography](#bibliography)


# Introduction 
This project is part of a series of roadmaps.

This project is not intended to be a guide, or a manual for using GIT.

In the [bibliography](#bibliography) of this project you can find all the sources used.

In this [image](./sources/roadmaps/GitHub_RoadMap.png) you can find in the roadmap on which the development of the project has been based

# Objective
The objective of this project is to reinforce the author's knowledge of Git, while at the same time attesting and demonstrating it.

It is not intended to be a practical guide to GIT and it is not intended to follow any specific course. We will simply try commands found in the official GIT documentation and try some online version control services.

# GIT
## Basic Commands
- &#x2611; **git init**: Initializes a new Git repository. It turns an existing directory into a Git repository and begins tracking an existing directory.
- **git clone [url]**: Clones a repository into a newly created directory, establishes remote-tracking branches for each branch in the cloned repository.
- &#x2611; **git add [file]**: Adds a file to the staging area. It tells Git that you want to include updates to a particular file in the next commit.
- &#x2611; **git commit -m "[commit message]"**: Records or snapshots the file permanently in the version history with a descriptive message.
- &#x2611; **git status**: Shows the status of changes as untracked, modified, or staged.
- &#x2611; **git config --global user.name "[name]"**: Sets the name that will be attached to your commits and tags.
- &#x2611; **git config --global user.email "[email address]"**: Sets the email you want attached to your commit transactions.
- **git diff**: Shows the file differences not yet staged.
- **git diff --staged (or --cached)**: Shows the differences between the staged files and the latest version present.
- &#x2611; **git log**: Displays the entire commit history using the default format.
- **git log --oneline**: Condenses each commit to a single line.
- **git rm [file]**: Deletes the file from your working directory and stages the deletion.
- **git branch**: Lists all the branches in your repo.
- **git checkout [branch-name]**: Switches to the specified branch and updates the working directory.
- **git merge [branch]**: Merges the specified branch’s history into the current branch.
- **git pull [Repository Link]**: Fetches and merges changes on the remote server to your working directory.
- &#x2611; **git push [alias] [branch]**: Transmits local branch commits to the remote repository branch.
- **git remote -v**: Lists all the remote connections you have to other repositories.

## Intermediate Commands
TODO
- &#x2612; **git stash**: Temporarily stores all modified tracked files.
- &#x2612; **git stash pop**: Restores the most recently stashed files.
- &#x2612; **git stash list**: Lists all stashed changesets.
- &#x2612; **git stash drop**: Discards the most recently stashed changeset.
- &#x2612; **git reset [file]**: Unstages the file, but preserves its contents.
- &#x2612; **git reset [commit]**: Undoes all commits after [commit], preserving changes locally.
- &#x2612; **git reset --hard [commit]**: Discards all history and changes back to the specified commit.
- &#x2612; **git rebase [branch]**: Applies your branch's commits on top of another base branch.
- &#x2612; **git fetch [alias]**: Downloads all the changes from the remote repository, but doesn't integrate them into your head.
- &#x2612; **git cherry-pick [commit]**: Applies the changes introduced by some existing commits.
- &#x2612; **git blame [file]**: Shows what revision and author last modified each line of a file.
- &#x2612; **git bisect**: Use binary search to find the commit that introduced a bug.

## Advanced Commands
TODO
- &#x2612; **git rebase -i [commit]**: Interactively rebase from the specified commit. This is useful for cleaning up a messy history.
- &#x2612; **git reflog**: Shows a log of changes to the local repository's HEAD.
- &#x2612; **git shortlog**: Summarizes git log output.
- &#x2612; **git show [commit]**: Shows various types of objects, such as commits, tags, and more.
- &#x2612; **git tag [commitID]**: Used to give tags to specified commits.
- &#x2612; **git rev-parse**: Used to parse Git revision specifications.
- &#x2612; **git submodule add [url] [path]**: Add a Git repository as a submodule at the specified path.
- &#x2612; **git gc**: Clean up unnecessary files and optimize the local repository.
- &#x2612; **git fsck**: Does an integrity check of the Git file system, identifying corrupted objects.
- &#x2612; **git archive**: Creates an archive of the specified format containing the tree structure for a named commit.
- &#x2612; **git rebase --continue/--abort/--skip**: Continue, abort, or skip a rebase after resolving conflicts.
- &#x2612; **git filter-branch**: Applies a filter to each commit in a specified branch.

## GitHub


## GitLab


# Markdown


# Bibliography
- https://dev.to/charalambosioannou/getting-started-with-git-and-github-a-simple-roadmap-lfn
