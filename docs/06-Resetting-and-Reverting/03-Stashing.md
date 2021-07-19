# Git Stashing
  - Take me to [Video Tutorial](https://kodekloud.com/topic/stashing/)

In this section, we will take a took at `git stash` command.

### git stash 

- If we don't want to commit now, we can stash all changes in the working area with `git stash` command. Modification in the working area, all get added to the stash. 

```
$ git stash
```
- With `git stash pop` command, to get back changes in our working area.

```
$ git stash pop
``` 

- To see the list of stash files, we can run the following command:

```
$ git stash list
```

- To see the content of the specific stash file, we can run the following command:

```
$ git stash show stash@{1}
```

- To pop the specific stash, we can run the following command:

```
$ git stash pop stash@{2}

```
