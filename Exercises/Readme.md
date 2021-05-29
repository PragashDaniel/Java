# CORE JAVA

Git hub repo dedicated for hands on java practise

## Things to note about this repo

- Need to know what is a programming language.
- Expected level is very basic, like what is variable and datatype.
- Problems encourages you to directly write functions and then classes directly.
- Most of the problems are designed in the way of language agnostic, So you use these problems for most of the OOPS language eg. Java,C#,Python etc.
- Plan is to parallelly familiarise developers most essential development tool Git. So you need to spend some time to learn about Git. 

## Workflow for using Git

- You find the problems in the main branch. so dont push the changes directly to main branch. But update your local main branch with frequent pull and push your feature branch changes to Remote ask for a PR to verify the code and merge the code in main.
- Steps: Pull the main(remote) => create a feature branch from main => Commit the changes in feature branch => Push your feature branch to remote => Raise Pull Request(PR) against main(remote) branch => Verify & Merge to main(remote) branch => Pull the updated code from main(remote).
- Beware of merge conflicts.

## Useful Git commands

- **git status** - check the current status of branch
- **git pull** - Pull remote git code from remote to update the local with current version of remote.
- **git checkout [branch_name]** - Switching between branches.
- **git checkout -b [branch_name]** - Create a new branch and switch to the currently created branch.
- **git add .** (or) **[filename]** - add your changes to staging, it is a staging environment before commiting changes.And **git add .** "." represents all changes in the git repo. Confirm with git status after git add.
- **git commit -m "[Meaningful commit message]"** - Commit or save your changes in your git repo.
- **git push** - push the committed chages to remote.
- **git reset** - to undo git add

## How to push your changes to remote

- check your current branch, use => **git status**
- if you want to switch to other branch, use => **git checkout [branch_name]** or create a new branch and switch use => **git checkout -b [branch_name]**
- After the changes add your changes, use => **git add .** (or) **[filename]**
- Commit your changes, use => **git commit -m "[Meaningful commit message]"**
- Push the committed changes to remote => **git push**


## Project structure:

- Excercise
  - Excercise#
    - Readme.md (contains problem definition)
    - solution.java (contains solution for the problem)
