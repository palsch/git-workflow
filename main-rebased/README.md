# Branch: main-rebased

This branch represents a main branch where `git rebase` was used.

Documentation: https://git-scm.com/book/en/v2/Git-Branching-Rebasing

## Short explanation

When using rebase git reruns all your commits from your not-main branch on top of the branch you are rebasing on.
That means, your base and your commit-hashes are changed. 
This overwrites the commit history of your not-main branch.
To push this new history to the server you have to use force-push `git push -f`.

Usually you rebase your not-main branch to the main branch to include the latest changes from the main branch to your not-main branch.


 
## Important rules for rebasing

  * never rebase the master/develop branch
  * never rebase feature branches, where more than one person is working on
  

## Commands 

```
git checkout not-main
git rebase main
```