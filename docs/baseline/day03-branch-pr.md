# Day 3 - Branch and Pull Request Practice

## Date

2026-05-03

## Goal

Today I practiced creating a branch, committing changes on that branch, pushing the branch to GitHub, opening a Pull Request, and merging it back into main.

## What I learned

Main branch:
The main version of the project.

Feature branch:
A separate branch used to make changes safely before merging them.

Pull Request:
A request to merge changes from one branch into another.

Merge:
Combining changes from a branch into main.

## Commands I practiced

```bash
git switch -c day03-branch-pr
git branch
git status
git add docs/baseline/day03-branch-pr.md
git commit -m "docs: add day 3 branch and pull request practice"
git push -u origin day03-branch-pr