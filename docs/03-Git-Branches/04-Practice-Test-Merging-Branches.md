  # Practice Test - Merging Branches
  - Take me to [Practice Test](https://kodekloud.com/topic/lab-merging-branches/)
    
 Solutions to practice test - merging branches
 - Run cd /home/sarah/story-blog; git checkout master and then list the files ls
    
   <details>
    
   ```
   $ cd /home/sarah/story-blog
   $ git checkout master
   $ ls
   ```
   
   </details>
   
- Run cd /home/sarah/story-blog and then list the files ls

  <details>

  ```
  $ cd /home/sarah/story-blog
  $ ls
  ```
  </details>
  
- Run git branch
    
  <details>
  
  ```
  $ git branch
  ```
  
  </details>
    
- Run git log

  <details>
  
  ```
  $ git checkout master
  $ git log
  $ git checkout story/frogs-and-on
  $ git log
  ```
  
  </details>

- Run git merge story/frogs-and-ox. Check git log now and it should show commit message as Merge branch 'story/frogs-and-ox' into master

  <details>
  
  ```
  $ git checkout master
  $ git merge story/frogs-and-ox
  $ git log
  ```
  
  </details>
  
- List the files in the master branch and make sure both the stories are visible.
  
  <details>
  
  ```
  $ ls
  ```
  
  </details>
