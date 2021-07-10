---
tags: coding git github systems
aliases: 
  - 
cssclass: 
---
`relevant links`[[coding]] [[Python MOC]]

### Terms
- [[version control]] the process for programmers to save copies of code
- `cd` change directory
- [[Repository]] the project or place where your project is stored
- `clone` brings a repository from a hosted software to a local stored folder.
- `add` adds and tracks files in Git
	- `git add .` tells Git to add all the files in project
- `commit` saves the current iteration of your files in Git
	- `git commit -m "string"` commits must have message
- `push` upload current committed files to Git
	- `git push orgin 'branch(main)'` is used to push to repo
	- `git push -u orgin (branch)` is used to store the repo information with your local storage so you don't have to type `orgin branch(etc)`
- `pull` takes projects from cloud Git repo to local storage
- `git remote add orgin (repo tag)` tells Git where to push local repo not previously connected to a remote repo

### Git Branching
- branching is used to have separate code bases originating from the ==Master Branch==. Adding another branch will start the same but can differ from the ==Master Branch== as new code is added to the new branch. 
- when adding new features to code, you can brick the original code, so adding a new branch allows you to safely implement new code.
- if you find a problem with your code you can add a ==Hot Fix Branch== to fix the issues found in the ==Feature Branch==, once fixed you can merge the Branches back into the ==Master Branch==
- `git checkout -b (branch name)` will take you out of the main branch and create a new branch
	- `git checkout (branch name)` will transfer you to the dedicated branch