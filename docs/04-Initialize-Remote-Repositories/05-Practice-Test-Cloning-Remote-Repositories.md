 # Practice Test - Cloning Remote Repositories
   - Take me to [Video Tutorial](https://kodekloud.com/courses/git-for-beginners/lectures/23427776)

Solutions to practice test - cloning remote repositories
- Run cd /home/max; git clone http://git.example.com/sarah/story-blog.git
  
  <details>
  
  ```
  $ cd /home/max
  $ git clone http://git.example.com/sarah/story-blog.git
  ```
  
  </details>
  
- Check the contents of the cloned repository. Confirm that you can see Sarah's story and history of commit by running git log and validate author info, commit message etc.

  <details>
  
  ```
  $ cd /home/max
  $ git log
  ```
  
  </details>

- Max has written his story about The 🦊 Fox and Grapes 🍇 View the file he created and its contents. You may read the story if you wish to. But don't spend all day 😝 

  <details>
  
  ```
  $ cd /home/max
  $ cat fox-and-grapes.txt
  ```
  
  </details>
  
 - Run git add fox-and-grapes.txt and then git commit -m 'Added fox-and-grapes story'

  <details>
  
  ```
  $ cd /home/max
  $ git add fox-and-grapes
  $ git config user.email "max@example.com"
  $ git config user.name "max"
  ```
  
  </details>

- Run the git remote -v command to check the remote repository
  
  <details>
  
  ```
  $ git remote -v
  ```
  
  </details>
  
- Run git push origin master
  
  <details>
  
  ```
  $ cd /home/max
  $ git push origin master
  ```
  
  </details>
  
- The account owner - Sarah needs to add you as a collaborator. While logged in to the Gitea UI as user sarah go to Settings -> Collaborators of the project and add max as collaborate with Write permissions.
  
  <details>
  
  ```
  From GUI --> Repositories --> sarah/story-blog --> settings --> collaborators
  ```
  
  </details>
  

- Simply run git push origin master to push and input login credentials
  
  <details>
  
  ```
  $ cd /home/max
  $ git push origin master
  ```
  
  </details>
