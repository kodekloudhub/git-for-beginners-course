# Practice Test - Stashing
  - Take me to [Practice Test](https://kodekloud.com/topic/lab-stashing/)

Solutions to practice test - Stashing
- Run the `cd` command to move into the **story-blog** directory and their check the content of the lion-and-mouse.txt file. Something is wrong written in the file.
  <details>
  	<summary>Solution</summary>

  ```
  $ cd story-blog
  $ cat lion-and-mouse.txt
  ```
  </details> 

- Run the `git stash` command to stash the current changes before heading over to the master branch.
  <details>
  	<summary>Solution</summary>

  ```
  $ git stash 
  ```
  </details> 

- Run the `git checkout` command to switch into the **master** branch. To fix the error and commit the changes.
  <details>
  	<summary>Solution</summary>
  
  ```
  $ git checkout master
  # Edit the file lion-and-mouse.txt and fix the typo
  $ git commit -am 'Fixed title error'
  ```
  </details>

- Run the `git checkout` command to switch into the **story/frogs-and-ox** branch and pop the stash to retrieve the stashed changes.
  <details>
  	<summary>Solution</summary>
  
  ```
  $ git checkout story/frogs-and-ox
  $ git stash pop
  # To retrieve frogs-and-ox.txt file
  ```
  </details>

- Run the `git checkout` command to switch into the **story/multi-part-story** branch and find the list of stories that were stashed.
  <details>
  	<summary>Solution</summary>

  ```
  $ git checkout story/multi-part-story
  $ git stash list
  ```
  </details>

- To figure out what files are stashed in which of these stashes. Run the `git stash` command with it's appropriate option.
  <details>
  	<summary>Solution</summary>

  ```
  $ git stash list
  $ git stash show stash@{0}
  $ git stash show stash@{1}
  $ git stash show stash@{2}
  ```
  </details>

- Run the `git stash` command to figure out what order were the files pushed to the stash. Order should be earliest to latest.
  <details>
  	<summary>Solution</summary>

  ```
  # stash@{0} is the last(latest), stash@{2} is the first(earliest)
  $ git stash show stash@{0}
  $ git stash show stash@{1}
  $ git stash show stash@{2}
  ```
  </details>

- To figure out, if we do pop the stash now, which file would be retrieved? Run the `git stash` command and it's approriate option to check the list of stashes.
  <details>
  	<summary>Solution</summary>
  
  ```
  $ git stash list
  $ git stash pop
  # The last stashed commits are popped first.
  ```
  </details>
