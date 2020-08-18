# Conclusion
  - Take me to [Video Tutorial](https://kodekloud.com/courses/1085975/lectures/23245007)

- In this session, we will take a quick recap of all the concepts that we learned. 

#### git install
- Git installing with the software package manager **brew**.

```
$ brew install git
``` 

#### git init
- After initialize it git-beginner directory with `git init` command. Git uses to store data.

```
$ git init
Initialized empty Git repository in /root/git-beginner/.git/
```
#### git remote
- We also covered, how we can initialize our remote repository to save our data in the remote server.

```
$ git remote add origin https://.../.../[name].git
```

#### git push
- We also learned about how we can push our data into the remote repository.

```
$ git push origin master
```

#### git clone
- We saw that how we can clone remote repository data into our local machine.

```
$ git clone https://.../.../[name].git
```

#### git branch
- We can work on our own version of the project by creating a new branch.

```
$ git branch checkout -b 
```

#### git commit
- To commit the changes.

```
$ git commit -m 'First commit'
```

#### git merge
- To merge the commit changes into the other branch.

```
$ git merge feature
```

#### git rebase 
- `git rebase` command creates a different GIT history compare to merging. 

```
$ git rebase master
```
- We also learned interactive rebasing, to get more control over the commits that we are rebasing. It will change the commits before rebasing them.

```
$ git rebase -i HEAD~4
```
#### git revert
- We also saw how we could do undo changes. We have to write a couple of characters of commit hash id. 

```
$ git revert 8ad58
```

#### git reset
- `git reset` is a bit harsh. If we reset with `--soft` flag changes still available in the working area and if we do with `--hard` flag, it will remove the changes forever.

```
$ git reset --soft HEAD~1

$ git reset --hard HEAD~1
```
##### We also learned how we could open the pull request in the Github platform, where's your team members can review your work.

##### Git is an extremely powerful tool. I hope this course has given you a Git introduction of the main concepts.