# GitHub Tutorial

_by Youssef Elkhouly_

---
## Git vs. GitHub
**Git** is a version control system that lets you keep track of your changes in code.

**Github** is a cloud-based system that helps you manage git repositories and work on them collaboratively.

---
## Initial Setup

**Steps I followed** [SSH KEY](https://github.com/hstatsep/ide50)

---
## Repository Setup
**Step 1** To create a new repo, you'll use the git init command in a new directory. git init is a one-time command you use during the initial setup of a new repo.

**Step 2** Use git add command after creating new files or relevant files and changes.

**Step 3** Use git commit command to save or confirm changes being made in the file on the staging area.

---
## Workflow & Commands

**git status** Not sure if you're working on a clean branch? Want to see what files have changed? Git status will show you a report.

**git add** Now that you've added or modified some files, you need to stage those commits into the "staging area". This could be done with git add.

**git commit** Now that you've made your changes and staged them, you want to commit or confirm these changes on your own file which is done with git commit.

**git push** This command will confirm and officially send your modifications to github.

**Step 1** Create a local git repository

**Step 2** Add a new file to the repository

**Step 3** Add the file to the stage

**Step 4** Create a commit

**Step 5** Create a new repository on github


---
## Rolling Back Changes

**git revert** Git revert command helps you undo any recent or existing commits.
Use "git add ." to add reverted changes to stage
Use "git commit" to commit changes
Use "git push" to push changes to github (confirming these changes)