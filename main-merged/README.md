# Branch: main-merged

This branch represents a main branch where `git merge` was used.

Documentation: https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging#_basic_merging

## Short explanation

Using merge you can get the latest changes from main branch to your not-main branch.
Each time you do that, this will create a new merge-commit in your not-main branch. 

## Commands

``` 
git checkout not-main
git merge main
```