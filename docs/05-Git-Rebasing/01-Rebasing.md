# Git Rebasing
  - Take me to [Video Tutorial](https://kodekloud.com/topic/rebasing/)

![r2](../../images/r2.PNG)

- In this section, we will take a look at git rebasing.

### Git merge
- We can merge the master branch into our own branch by `git merge` command. 
- This creates a new merge commit, to merge these changes into the our own branch. Another way to achieving this, by rebasing branches.
```
$ git merge master
```

### Git rebase
- Basically in the rebasing, we are putting branch into top of the another branch one. 
- After performing this, current branch is containing all the changes that were made in the master branch.

```
$ git rebase master
```
- In the GIT, each commit has the unique identifier. This unique identifier is a hash that contains the information about the commit.
- When its merge, this unique identifer won't be modified. In the other words, we are not modifying the history of the GIT commits. When we are merging.
- When we are rebasing, actually we are copying commits from one branch to the another branch. Each time a hash value will update. 