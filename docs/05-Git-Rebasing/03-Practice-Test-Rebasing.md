# Practice Test - Rebasing
  - Take me to [Practice Test](https://kodekloud.com/topic/lab-rebasing/)

Solutions to practice test - Git Rebasing
- Click on the **Gitea Portal UI** button and enter the credentials given in the screen. Open the **sarah** story-blog repository. Click on the **Commits**.
  <details>
    <summary>Solution</summary>
  
  ```
  $ Last commit has done by tom
  ```  
  </details>

- Run the command to pull all the changes from remote to our local master branch.
  <details>
     <summary>Solution</summary>

  ```
  $ cd /home/sarah/story-blog
  $ git checkout master
  $ git pull origin master
  ```
  </details>

- Run the following command to check the availability of the story-index.txt file in the current working directory.
  <details>
    <summary>Solution</summary>

  ```
  $ ls 
  ```
  </details>

- Run the following command to checkout the story/hare-and-tortoise branch and count the total of commits.
  <details>
     <summary>Solution</summary>

  ```
  $ git checkout story/hare-and-tortoise
  $ git log --oneline
  ```
  </details>

- Run the following command to checkout the story/hare-and-tortoise branch and then rebase master branch.
  <details>
     <summary>Solution</summary>

  ```
  $ git checkout story/hare-and-tortoise
  $ git rebase master
  ```
  </details>

- Run the following command to check the current status of commit.
  <details>
    <summary>Solution</summary>

  ```
  $ git log
  ```
  </details>

- Run the following command to squash all the commits into a single commit. It opens the editor. Leave the first line and change the second and third lines to use `squash` instead of `pick` then save the file and exit with `:wq`. It will open again a file in the editor. Add the commit message "Add hare-and-tortoise story" with press `i` then save the file and exit with `:wq`.
  <details>
   <summary>Solution</summary>

  ```
  $ git rebase -i HEAD~3 
  ```
  </details>
