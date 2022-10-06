# Session Notes GIT Pull / New Branch / Worklflow

## GIT Worklflow:

1. GIT Init: create a new repository
2. GIT Add: add a new file to the repository
3. GIT commit: commit the new file to the repository
4. GIT Push: Send the file to the remote repository

## Git Branching

Git branches are important to implement new features. Branches can be used to test and review features before they are merged into the main branch.

## Create a new branch:

git switch -c "branch-name"

## Switch between branches:

git switch "branch-name"

## Workflow for a pull request

1. create a new branch with git switch -c "branchname"
2. Make your code changes
3. Push the changes and the new branch with git push -u origin "branchname" -> only needed once, after that you can use git push
4. Create a pull request on Github and share it with your team
5. Review all changes, implement new changes if needed, push it again and update the pull request with a specific note on Github
6. Merge it into "main"
7. On your local machine, make a git pull of the main branch to save all changes
8. Delete the new branch on Github and locally
