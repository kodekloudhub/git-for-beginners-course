# Practice Test - Branches
  - Take me to [Practice Test](https://kodekloud.com/topic/lab-branches-checkout-push-branch/)
  
Solutions to practice test - Branches
- Refer the previous lecture, Branch is nothing but a pointer to a specific commit in GIT
  
  <details>
  
  ```
  Pointer to a specific commit in git
  ```
  
  </details>
  
- By default the branch used is master
  
- Simply run cd /home/sarah/story-blog; git log --name-only
  
  <details>
  
  ```
  $ cd /home/sarah/story-blog
  $ git log --name-only
  ```
  
  </details>
  
- Check branch in the git log --decorate output

  <details>
  
  ```
  $ git log --decorate
  ```
  
  </details>
  
- Run git checkout -b story/frogs-and-ox

  <details>
  
  ```
  $ git checkout -b story/frogs-and-ox
  ```
  
  </details>
  
- Check branch HEAD pointer in git log output

  <details>
  
  ```
  $ git log
  ```
  
  </details>

- Run git add frogs-and-ox.txt; git commit -am 'Add incomplete frogs-and-ox story'

  <details>
  
  ```
  $ git add frogs-and-ox.txt
  $ git commit -am 'Add incomplete frogs-and-ox story'
  ```
  
  </details>

- Run git checkout master

 <details>
  
  ```
  $ git checkout master
  ```
  
  </details>

- Use vi editor to edit the file and fix the typo. Then run the command git commit -am 'Fix typo in story title' 

  <details>
  
  ```
  $ git commit -am 'Fix typo in story title'
  ```
  
  </details>

- Run the command git checkout story/frogs-and-ox

  <details>
  
  ```
  $ git checkout story/frogs-and-ox
  ```
  
  </details>

- Run the command git commit -am 'Completed frogs-and-ox story'

  <details>
  
  ```
  $ git commit -am 'Completed frogs-and-ox story'
  ```
  
  </details>

- Change to directory cd /home/sarah/website and run git branch command

  <details>
  
  ```
  $ cd /home/sarah/website
  $ git branch
  ```
  
  </details>

- Checkout to directory git checkout feature/signout; git log --graph --decorate

  <details>
  
  ```
  $ git checkout feature/signout
  $ git log --graph --decorate
  ```
  
  </details>

- Checkout to directory git checkout feature/signout; git log --graph --decorate

  <details>
  
  ```
  $ git checkout feature/signout
  $ git log --graph --decorate
  ```


