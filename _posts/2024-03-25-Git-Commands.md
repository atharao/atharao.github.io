---
title: Mastering Git | Essential Commands You Should Know
date: 2024-03-24 20:14 +0300
categories: [Development Tools, Version Control, Programming]
tags: [Git, Version Control, Git Commands, Software Development]
---


## Discovering Git

I began my journey with Git back in 2018, right after I was chosen for Google Code In. This experience opened the door to the world of open-source projects, including events like Hacktoberfest, and taught me how to manage my code both locally and on platforms like GitHub. So, I wanted to share my knowledge with you guys, hoping it will illuminate your path as it did mine.

## What is Git?

Git is a distributed version control system designed to handle everything from small to very large projects with speed and efficiency. It's a tool that allows multiple developers to work on a shared project without stepping on each other's toes. It tracks changes in files and allows for branching, merging, and versioning, making it easier to manage complex projects and collaborate with others.


![Understanding Git](/assets/img/posts/2024-03-25-Git-Commands/git.png)
_Git Commands_

## Most Used Commands

These commands are essential for daily Git operations.

### `git init`
- **Usage**: Initializes a new Git repository.
- **When to use it**: Starting a new project or deciding to track an existing project with Git.

### `git clone [URL]`
- **Usage**: Copies a Git repository from a remote source.
- **When to use it**: When you want to work on a copy of an existing repository.

### `git add [file]`
- **Usage**: Adds files to the staging area.
- **When to use it**: After making changes or adding new files to your project.

### `git commit -m "[message]"`
- **Usage**: Records changes to the repository with a descriptive message.
- **When to use it**: After adding changes and before pushing to a remote repository.

### `git push [remote] [branch]`
- **Usage**: Sends local branch commits to the remote repository branch.
- **When to use it**: To share your commits with others or backup your work.

### `git pull [remote] [branch]`
- **Usage**: Fetches and integrates changes from a remote repository to your local branch.
- **When to use it**: To keep your local repository up-to-date with the remote repository.

### `git branch [branch-name]`
- **Usage**: Creates a new branch.
- **When to use it**: When starting work on a new feature or fix.

### `git checkout [branch-name]`
- **Usage**: Switches to another branch.
- **When to use it**: To work on a different part of your project.

### `git merge [branch]`
- **Usage**: Combines changes from one branch into another.
- **When to use it**: To integrate completed features into your main project.

### `git status`
- **Usage**: Displays the state of the working directory and staging area.
- **When to use it**: To check which changes are staged, unstaged, or untracked.

## Average Used Commands

These commands are commonly used but may not be necessary for everyday work.

### `git diff`
- **Usage**: Shows changes between commits, commit and working tree, etc.
- **When to use it**: To see what has changed before committing.

### `git stash`
- **Usage**: Temporarily shelves changes so you can work on a different task.
- **When to use it**: To switch contexts without committing half-done work.

### `git stash pop`
- **Usage**: Applies stashed changes back to your working directory.
- **When to use it**: To resume work on a previously stashed project state.

### `git reset [file]`
- **Usage**: Unstages a file.
- **When to use it**: If you decide not to commit changes to a file.

### `git reset --hard [commit]`
- **Usage**: Resets the index and working directory to a specific state.
- **When to use it**: To discard all local changes and revert to a previous commit.

### `git log`
- **Usage**: Shows the commit history.
- **When to use it**: To review changes or find specific changes.

### `git rebase [branch]`
- **Usage**: Reapplies commits on top of another base tip.
- **When to use it**: To integrate changes from one branch into another.

### `git fetch [remote]`
- **Usage**: Downloads objects and refs from another repository.
- **When to use it**: To fetch changes without merging them into your local branch.

## Least Used but Useful Commands

These commands are highly valuable for specific scenarios.

### `git remote add [shortname] [url]`
- **Usage**: Adds a new remote repository.
- **When to use it**: To collaborate with others on a project hosted on a remote server.

### `git tag [tag-name]`
- **Usage**: Marks a specific commit with a simple, memorable name.
- **When to use it**: To mark release points like `v1.0`.

### `git cherry-pick [commit]`
- **Usage**: Applies the changes introduced by some existing commits.
- **When to use it**: To integrate a commit from one branch into another without merging.

### `git rebase --interactive [base]`
- **Usage**: Reapply commits on top of another base tip, allowing for complex history rewriting.
- **When to use it**: To clean up a messy commit history before merging it into a main branch.

### `git stash list`
- **Usage**: Lists all stashed changes.
- **When to use it**: To see what work has been stashed.

### `git stash drop [stash@{<number>}]`
- **Usage**: Discards a specific stash.
- **When to use it**: When you no longer need the stashed changes.

### `git reflog`
- **Usage**: Shows a log of changes to the HEAD.
- **When to use it**: To recover lost commits.

### `git show [commit]`
- **Usage**: Shows various types of objects (commits, tags, etc.) in a human-readable format.
- **When to use it**: To view detailed information about a commit.

### `git clean -fd`
- **Usage**: Removes untracked files from the working directory.
- **When to use it**: To clean your repository by removing files that are not under version control.

### `git fetch --prune`
- **Usage**: Fetches and removes any remote-tracking references that no longer exist on the remote.
- **When to use it**: To clean up outdated references.

### `git gc`
- **Usage**: Cleans up unnecessary files and optimizes the local repository.
- **When to use it**: To improve performance or reduce disk usage.

### `git worktree add [path] [branch]`
- **Usage**: Manages multiple working trees attached to the same repository.
- **When to use it**: To work on multiple branches without switching contexts in the same directory.

## Wrapping Up
Remember, mastery comes with practice, so I encourage you to use these commands in your daily work, explore Git's vast capabilities further, and share your experiences with others.
 
If you've got any questions or need more details, feel free connect with me on [Twitter](https://twitter.com/atharao_) or [LinkedIn](https://www.linkedin.com/in/atharao/).
