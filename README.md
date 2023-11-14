# Git Branching Score Keeper

This exercise is intended to help practice git branching and merging using the CLI (terminal).

## Set-up

Start by **forking** this repository. Then **clone** the forked repository to your computer. 


## Overview

Create a **new feature branch** for each of the tasks listed below and then merging the changes back into **main** after each one. 

You will only be making changes to the **index.html** and **styles.css** files. 

**Don't over think this assignment. The focus is not on the tasks. The goal is to practice branching.**


## Task List

The client finally got back to us with answers to our questions. We can now make edits required to complete the Score Keeper website.

> **NOTE: COMPLETE THE TASKS IN ORDER & MERGE EACH BRANCH BACK INTO MAIN BEFORE DOING THE NEXT ONE**

### Base Mode

- [ ] **feature-team-names** - Team names have been assigned, they should read **Team Tomato** and **Team Plum**
   - After adding and committing, merge this branch back to `main`
- [ ] **feature-page-title** - The title of the page should read **Battle of the Fruits**
   - After adding and committing, merge this branch back to `main`
- [ ] **feature-bg-colors** - The team divs (with classes `.team1` & `.team2`) should have background colors that match the team names
   - After adding and committing, merge this branch back to `main`
- [ ] **feature-footer** - Create a footer at the bottom of the page that reads 'Made by Tomatoes inc.'
   - After adding and committing, merge this branch back to `main`

### Pushing to GitHub

If you cloned from your own account (if you forked first), then you can push your local commits back to GitHub. 

When everything is merged back into the **main** branch, push up your completed project. 

Make sure you have checked out **main**

> `$ git checkout main`

Then push:

> `$ git push origin main`


### Stretch Goals

- [ ] **feature-styling** - Add styling to make the page look better
   - After adding and committing, merge this branch back to `main`

### Additional Resources

- More Git practice: [https://try.github.io/levels/1/challenges/1](https://try.github.io/levels/1/challenges/1)
- Pull requests: [https://help.github.com/articles/creating-a-pull-request/](https://help.github.com/articles/creating-a-pull-request/)


## Git Branching Cheatsheet

- `git branch BRANCH-NAME` - Create a branch with the name of **BRANCH-NAME**
- `git branch` - Display the branch you're currently on
- `git branch -a` - Show all available branches that have been created
- `git checkout BRANCH-NAME` - Switch to the branch with name **BRANCH-NAME**
- `git merge --no-ff BRANCH-NAME` - Merge **BRANCH-NAME** into the current branch (use `git branch` to determine the current branch)
   - If there are no conflicts, you may be thrown into `ViM`. Type `:wq` to accept the merge. Otherwise you may need to resolve the conflicts (check the section below)
- `git pull origin BRANCH-NAME` - Pull down changes from the remote
