# Git Cherry Picking
  - Take me to [Video Tutorial](https://kodekloud.com/topic/cherry-picking/)

  ![r3](../../images/r3.PNG)

- In this section, we will take a look at `git cherry-pick` command.
- One branch has certain changes and you would like to apply into the other branch. But you don't want to all the changes that you made in that branch. In the certain things, we use `cherry-pick` command to copy of that commits onto own branch.  
- We use hash of the commit, that we want to use for a cherry-pick. After running this command, it will create a copy of the commit into the specified branch.

```
$ git cherry-pick aaba5
```
