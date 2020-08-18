# Pull requests
  - Take me to [Practice Test](https://kodekloud.com/courses/git-for-beginners/lectures/23429436)
  
Solutions to practice test - pull requests

- Run cd /home/max; git clone http://git.example.com/sarah/story-blog.git
  
  <details>
  
  ```
  $ cd /home/max
  $ git clone http://git.example.com/sarah/story-blog.git
  ```
  
  </details>
  
- View the file he created and its contents. You may read the story if you wish to. What's the status of the file in the git repo?

  <details>
  
  ```
  $ cd /home/max/story-blog
  $ git status
  ```
  
  </details>

- Run git checkout -b story/fox-and-grapes; git add .; git commit -m 'Added fox-and-grapes story'

  <details>
  
  ```
  $ cd /home/max/story-blog
  $ git checkout -b story/fox-and-grapes
  $ git add . 
  $ git commit -m 'Added fox-and-grapes story'
  ```
  
  </details>

- Run the command git push origin story/fox-and-grapes to push and input login credentials

  <details>
  
  ```
  $ cd /home/max/story-blog
  $ git push origin story/fox-and-grapes
  ```
  
  </details>

- Follow below steps to create PR

  <details>

  - Login to Git Portal UI with max user

  - Go to the story-blog repository

  - Click on Pull requests

  - Click on New Pull request

  - Put PR pull from branch: story/fox-and-grapes

  - Put PR merge into branch: master

  - Click on New Pull Request

  - Add PR title as Added fox-and-grapes story

  - Click on Create Pull request

  </details>
  
- Go to the newly created PR

  <details>
  
  - Click on Reviewers on the right

  - Add tom as a reviewer to the PR

  </details>
  
- Sign out of Git Portal UI as max user

  <details>
  
  - Login as tom user

  - Go to story-blog repo and click on Pull Requests

  - Click on the PR - Added fox-and-grapes story

  - Click on Files changed tab and then the green drop down button Review. Add any approval message and click on the Approve button to approve the PR. You may need to scroll down to see the Approve button.

  </details>
  
- Logout of tom user

  <details>

  - login with the user sarah

  - Select the PR

  - Click on the green button Merge Pull Request and then confirm again by clicking on the green button Merge Pull Request to merge the PR

  - PR status should be shown as Merged

  </details>

-
