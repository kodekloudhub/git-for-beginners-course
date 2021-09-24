# Practice Test - Resetting and Reverting
  - Take me to [Practice Test](https://kodekloud.com/topic/lab-resetting-and-reverting/)

Solutions to practice test - Resetting and Reverting
- Run the `cd` command to move into the story-blog directory.
  <details>
  	<summary>Solution</summary>
  
  ```
  $ cd story-blog
  ```
  </details>

- Run the `git log` command with it's appropriate option to check the history of commits with changed files lists. 
  <details>
  	<summary>Solution</summary>
  
  ```
  $ git log --name-only
  # count the number of files changed in the last commit.
  ```
  </details>

- Run the `git revert` command to undo all the changes made in the previous commit. It will open the file in the editor, we don't need to change anything. Save the file with default commit message.
  <details>
  	<summary>Solution</summary>

  ```
  $ git log 
  $ git revert <last-commit-id>
  ```
  </details>

- Run the `git reset` command with it's appropriate option which can be used to retain changes that were made on target commit after the reset operation.
  <details>
  	<summary>Solution</summary>

  ```
  $ git help reset
  $ git reset --soft
  ```
  </details>

- Run the `git reset` command with it's appropriate option which can be used to drop changes that were made on target commit after the reset operation.
  <details>
  	<summary>Solution</summary>

  ```
  $ git help reset
  $ git reset --hard
  ```
  </details>

- Run the `git reset` command to revert the last commit but retain the unfinished changes. The last commit must not be part of the GIT history.
  <details>
  	<summary>Solution</summary>

  ```
  $ git help reset
  $ git reset --soft HEAD~1
  ```
  </details>

- Run the `git commit` command to commit the latest changes done in the file.
  <details>
  	<summary>Solution</summary>

  ```
  $ git commit -am 'Finish hair-and-tortoise story'
  ```
  </details>

- Run the `git log` command to check the logs and count the number of commits made since she previously finished her story.
  <details>
  	<summary>Solution</summary>

  ```
  $ git log
  $ git log --name-only        # With file name
  ```
  </details>

- Run the `git reset` command with it's appropriate option to remove all commits and changes she made since the commit "Finish hair-and-tortoise story".
  <details>
  	<summary>Solution</summary>
  
  ```
  $ git log
  $ git reset --hard HEAD~3
  ```
  </details>