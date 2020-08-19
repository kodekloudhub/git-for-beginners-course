# Practice Test - Git Log
  - Take me to [Practice Test](https://kodekloud.com/courses/1085975/lectures/23241040)
  
Solutions to practice test - git log

- We have initialised git repo in /home/sarah/story-blog. Check git log command output in that directory
  
  <details>
  
  ```
  $ cd /home/sarah/story-blog
  $ git log
  ```
  
  </details>

- Run git add .;git commit -m "Added the lion and mouse story"
  
  <details>
  
  ```
  $ git add .
  $ git commit -m "Added the lion and mouse story"
  ```
  
  </details>
  
- Check git log command output in that directory

  <details>
  
  ```
  $ git log
  ```
  
  </details>
  
- Which info is not displayed in git log?

  <details>
  
  ```
  List of changed files
  ```

- You can list the changed files as well using the --name-only option with the git log command
  
  <details>
  
  ```
  $ git log --name-only
  ```
  
  </details>
  
- Which branch has the changes been committed to?
  
  <details>
  
  ```
  $ git log
  ```
  
  </details>
  
- Who is the Author of the commit in git repo?
  
  <details>
  
  ```
  $ git log
  ```
  
  </details>
  
- Check git log where commit message is Added a new story
  
  <details>
  
  ```
  $ git log --name-only
  ```
  
  </details>
  
- What is the option for git log command to display the logs in compact way (one log per line)?
  
  <details>
  
  ```
  $ git log --oneline
  ```
  
  </details>
  
- Go to cd /home/sarah/learning-app-ecommerce and run git log
  
  <details>
  
  ```
  $ cd /home/sarah/learning-app-ecommerce
  $ git status
  $ git log
  ```
  
  </details>
  
- You may list the last few commits alone using the --max-count option like this git log -n 3 or git log --max-count 3
  
  <details>
  
  ```
  $ git log -n 3
  $ git log --max-count 3
  ```
  
  </details>
  
- Go to cd /home/sarah/learning-app-ecommerce and run git log -n 1
  
  <details>
  
  ```
  $ git log -n 1
  $ git log --max-count 1
  ```
  
  </details>


- Go to cd /home/sarah/learning-app-ecommerce and run git log --name-only and look for the commit that changed the file js/theme.js

  <details>
  
  ```
  $ cd /home/sarah/learning-app-ecommerce
  $ git log --name-only
  ```
  
  </details>


  
