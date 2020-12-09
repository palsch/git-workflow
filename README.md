# GIT workflow examples

This repository explains two topics:

0. **merge-strategy** vs **rebasing-strategy**
0. squashing development-commits: yes or no


## Example branches

0. main-merged
0. main-rebased
0. main-not-squashed
0. main-squashed


## Rules for main/develop branch

To keep a clean commit history there are some rules that should be followed.

* Avoid merge commits (see [main-merged](./main-merged/README.md) vs [main-rebased](./main-rebased/README.md))
* Don't merge development-commits (see [main-not-squashed](./main-not-squashed/README.md) vs [main-squashed](./main-squashed/README.md))


## Rules for release branches

Release branch is a special temporary branch that is only used to build a release artifact and is deleted afterwards.

Here you should always use the **merge strategy**.