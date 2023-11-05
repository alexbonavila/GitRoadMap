## Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [GIT](#git)
  - [Basic Commands](#basic-commands)
  - [Intermediate Commands](#intermediate-commands)
  - [Advanced Commands](#advanced-commands)
  - [GitHub](#github)
  - [GitKraken Client](#gitkraken-client)
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
- ✅ **git init**: Initializes a new Git repository. It turns an existing directory into a Git repository and begins tracking an existing directory.
- ✅ **git clone [url]**: Clones a repository into a newly created directory, establishes remote-tracking branches for each branch in the cloned repository.
- ✅ **git add [file]**: Adds a file to the staging area. It tells Git that you want to include updates to a particular file in the next commit.
- ✅ **git commit -m "[commit message]"**: Records or snapshots the file permanently in the version history with a descriptive message.
- ✅ **git status**: Shows the status of changes as untracked, modified, or staged.
- ✅ **git config --global user.name "[name]"**: Sets the name that will be attached to your commits and tags.
- ✅ **git config --global user.email "[email address]"**: Sets the email you want attached to your commit transactions.
- ✅ **git diff**: Shows the file differences not yet staged.
- ✅ **git diff --staged (or --cached)**: Shows the differences between the staged files and the latest version present.
- ✅ **git log**: Displays the entire commit history using the default format.
- ✅ **git log --oneline**: Condenses each commit to a single line.
- ✅ **git rm [file]**: Deletes the file from your working directory and stages the deletion.
- ✅ **git branch**: Lists all the branches in your repo.
- ✅ **git branch -M main**: Rename the current branch by default "master" to "main"
- ✅ **git branch [branch-name]**: Adds new branch
- ✅ **git checkout [branch-name]**: Switches to the specified branch and updates the working directory.
- ✅ **git merge [branch]**: Merges the specified branch’s history into the current branch.
- ✅ **git pull [Repository Link]**: Fetches and merges changes on the remote server to your working directory.
- ✅ **git push [alias] [branch]**: Transmits local branch commits to the remote repository branch.
- ✅ **git remote -v**: Lists all the remote connections you have to other repositories.
- ✅ **git remote add [alias] [Repository Link]**: Adds a new remote repository to local repository

## Intermediate Commands
- ✅ **git stash**: Temporarily stores all modified tracked files.
- ✅ **git stash pop**: Restores the most recently stashed files.
- ✅ **git stash list**: Lists all stashed changesets.
- ✅ **git stash drop**: Discards the most recently stashed changeset.
- ✅ **git reset [file]**: Unstages the file, but preserves its contents.
- ✅ **git reset [commit]**: Undoes all commits after [commit], preserving changes locally.
- ✅ **git reset --hard [commit]**: Discards all history and changes back to the specified commit.
- ✅ **git rebase [branch]**: Applies your branch's commits on top of another base branch.
- ✅ **git fetch [alias]**: Downloads all the changes from the remote repository, but doesn't integrate them into your head.
- ✅ **git cherry-pick [commit]**: Applies the changes introduced by some existing commits.
- ✅ **git blame [file]**: Shows what revision and author last modified each line of a file.
- ✅ **git bisect**: Use binary search to find the commit that introduced a bug.

## Advanced Commands
- ✅ **git rebase -i [commit]**: Interactively rebase from the specified commit. This is useful for cleaning up a messy history.
- ✅ **git reflog**: Shows a log of changes to the local repository's HEAD.
- ✅ **git shortlog**: Summarizes git log output.
- ✅ **git show [commit]**: Shows various types of objects, such as commits, tags, and more.
- ✅ **git tag**: List tags from system git
- ✅ **git tag [tagID] [commitID]**: Used to give tags to specified commits.
- ✅ **git rev-parse**: Used to parse Git revision specifications.
- ✅ **git submodule add [url] [path]**: Add a Git repository as a submodule at the specified path.
- ✅ **git gc**: Clean up unnecessary files and optimize the local repository.
- ✅ **git fsck**: Does an integrity check of the Git file system, identifying corrupted objects.
- ✅ **git archive**: Creates an archive of the specified format containing the tree structure for a named commit.
- ✅ **git rebase --continue/--abort/--skip**: Continue, abort, or skip a rebase after resolving conflicts.
- ✅ **git filter-branch**: Applies a filter to each commit in a specified branch.

## GitFlow
- ✅ **git flow init**: Configure the git flow extension
- ✅ **git branch develop**: 
- ✅ **git push -u origin develop**: 

## GitHub
- Fork third party project
  - Forked laravel official repository: https://github.com/alexbonavila/laravel

## GitKraken Client

## GitLab


## Markdown
The following code are Markdown structures that I do not usually use.

- Ordered list

1. Item 1
2. Item 2
3. Item 3
   1. Item i
   2. Item ii

- Blockquotes

> We're living the future so
> the present is our past.

- Inline Code

I think you should use an `<addr>` element here instead.

- Syntax Highlighted Code Block

```javascript
function fancyAlert(arg) {
  if (arg) {
    $.facebox({div:'#foo'})
  }
}
```

# Bibliography
- https://dev.to/charalambosioannou/getting-started-with-git-and-github-a-simple-roadmap-lfn
- https://git-scm.com/docs/git
- https://git-scm.com/docs
- https://docs.github.com/es
- https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow