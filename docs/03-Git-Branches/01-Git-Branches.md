# Git Branches
  - Take me to [Video Tutorial](https://kodekloud.com/courses/1085975/lectures/23241083)
 
In this section, we will take a look at git branches

## Branches
- Keep project versioned using branch
- A branch is basically a pointer to the last commit
  
  ![gitb1](../../images/gitb1.PNG)
  
- If you are working on a feature, you might work on a feature branch (eg. feature/signup), once the features are tested, you can merge to master branch

  ![gitb2](../../images/gitb2.PNG)
  
- To create a new branch
  ```
  $ git branch sarah
  ```
  
- To create a new branch and switch to it
  ```
  $ git checkout -b sarah
  ```
  
- To list of all of our branches
  ```
  $ git branch
  ```
  
  ![gitb3](../../images/gitb3.PNG)
  
- Switch to exisiting branch
  ```
  $ git checkout sarah
  ```

- Delete a branch
  ```
  $ git branch -d max
  ```
  
  
