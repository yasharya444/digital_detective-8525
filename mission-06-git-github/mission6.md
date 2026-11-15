## Task 6.1 - Understand the Basic Git workflow

| Git operation | What it does  |
|:---:|:---:|
| Check repository status (git status) | Shows which files are changed, staged or untracked, and which branch I am on. |
| Stage selected changes (git add README.md) | Picks the specific changes I want included in my next save point. |
| Create a commit (git commit -m "Completed task 6.1 by creating commit") | Saves the staged changes permanently in history with a message. |
| View commit history (git log --oneline) | Lists past commits with their messages in a short form. |

# Task 6.2 - Create and use a branch 
- command used: git checkout -b update-about

# Task 6.3 - Create a pull request
- A branch is a separate version of a project where you can make changes without affecting the original code.
Instead of  modifying the main code directly, you can create separate branches and work independently.
- Main branch: Contains the original, stable project.
- New branch: Allows you to work on new features or fixes without affecting the main branch.

- A Pull Request is a request to merge the changes made in one branch into another branch, usually the main branch.

- It allows other team members to review your code, suggest improvements, and approve the changes before they become part of the main project.

- A branch lets developers work separately, while a pull request allows them to review and combine their work into the main project.

# Task 6.4 - Build Your own git command glossary.
|command|Purpose|
|:---:|:---:|
|git init|Creates a new Git repository to start tracking a project's changes|
|git status|Shows which files are modified, staged, or untracked.|
|git add .|Selects the changes that will be included in the next commit.|
|git commit -m ""|Saves the staged changes as a snapshot in the project's history|
|git log|Displays previous commits and their details|
|git branch|displays the existing branches|
|git branch branch-name|Creates a new branch|
|git switch "branch_name"|Moves from one branch to another.|
|git push|Uploads local commits to a remote repository like GitHub|
|git pull|Downloads and integrates changes from a remote repository into your local branch.|
