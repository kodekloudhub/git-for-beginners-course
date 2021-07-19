# Practice Test - Cherry Picking
  - Take me to [Practice Test](https://kodekloud.com/topic/lab-cherry-picking/)

Solutions to practice test - Cherry Picking
- Move into the directory with `cd` command and check the content of the given file name with `cat` command.
  <details>
  	<summary>Solution</summary>
  
  ```
  $ cd story-blog
  $ cat story-index.txt
  ```
  </details>

- Run the following command to check the hash value of the commit that contains commit message "Updated the story index file" in the master branch.
  <details>
  	<summary>Solution</summary>
  
  ```
  $ git log master --oneline
  
  ```
  </details>

- Run the following command to switch into the given branch and perform cherry-pick command.
  <details>
  	<summary>Solution</summary>
  	
  ```
  $ git checkout story/hare-and-tortoise
  $ git cherry-pick < write commit hash value identified in the previous step >
  ```
  </details>