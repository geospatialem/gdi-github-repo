# 'Git' from Girl Develop It, Minneapolis, [Slides](http://amlyhamm.com/gdi/fall_in_love_with_git)

## Version Control

### Benefits
* Collaborate
* Track Changes

### Types
* Centralized
* Distributed (e.g. GitHub)

## Vocabulary
* **Repo**: project folder (Git leprechauns)
* **Clone**: A copy of the Repo
* **Commit**: Change to the file(s), saving it/them.
* **Git**: A program to track your Changes
* **Hashed commit**: Unique IDs for commits (GitHub does this)

## SSH Keys
Like a fingerprint, adds extra security to your GitHub account

## Shortcuts
* Up arrow to get the last command
* Tab to finish the phrase

## How To Make a Repo

### 1. Create a Repo
`mkdir [repo-name]`  
`cd [repo-name]`  

### 2. Initialize
`git init`  
`git status`  

### 3. Add a new file
`git add [file-name.ext]`  

## Undo Your Changes
Nobody's perfect. Sometimes you'll want to "undo" or "revert" some changes you've made.
P.S. AMAZING!

### Unstaged files
`git checkout [file-name]`  

### Staged files
`git reset HEAD [file-name]`  
`git checkout [file-name]`  

### Revert to a specific commit
`git revert [commit-hash]`  

## Branches
A parallel version of a repo. `Master` is GitHub's default branch. **A branch is a new ending to a novel.**
* Same repo, different branch
* `Master` branch is left alone
* Use a branch when you are ready

### Create a Branch
`git checkout -b`  
`git status` will tell you the branch that you are in.

### Switch Branches
`git branch`: see all branches in the repo
`git checkout master`: checkout the `master` branch

### Delete a Branch
`git branch -d [branch-name]`

## Merge a Branch
