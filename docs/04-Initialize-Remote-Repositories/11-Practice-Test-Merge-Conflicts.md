 # Practice Test - Merge Conflicts
   - Take me to [Practice Test](https://kodekloud.com/courses/git-for-beginners/lectures/23429496)
   
 Solutions to practice test - merge conflicts
 
 - Run git add story-index.txt; git commit -am 'Add index of stories'

   <details>
   
   ```
   $ git add story-index.txt
   $ git commit -am 'Add index of stories'
   ```
   
   </details>
   
 - Run the command git push origin master. It should fail with the rejected message

   <details>
   
   ```
   $ git push origin master
   ```
   
   </details>

- Read the error message and identify the cause of the failure.
  
  <details>
   
   ```
   The remote contains the work you do not have locally
   ```
   
   </details>
  
- Run git pull origin master

   <details>
   
   ```
   $ git pull origin master
   ```
   
   </details>

- What was the result of the Pull operation?

   <details>
   
   ```
   Merge Conflict
   ```
   
   </details>

- Run git log origin/master

   <details>
   
   ```
   $ git log origin/master
   ```
   
   </details>

- Inspect the file (use vi editor or just cat story-index.txt) and select the most appropriate statement below. The first section shows Max's data and the second section shows Sarah's data.

   <details>
   
   ```
   sarah missed the Donkey and Dog story, Max mis-spelt the lion and mouse story
   ```
   
   </details>

- Update the contents of the file (use vi editor) to keep the correct version of the Lion and Mouse story and keep the Donkey and Dog story as well. Remove all the extra lines added by GIT

   <details>
   
   ```
   $ cat story-index.txt
   1. The Lion and the Mouse
   2. The Frogs and the Ox
   3. The Fox and the Grapes
   4. The Donkey and the Dog
   ```

- Run the command git commit -am 'Resolved merge conflicts and merged story index'

   <details>
   
   ```
   $ git commit -am 'Resolved merge conflicts and merged story index'
   ```
   
   </details>

- Run the command git push origin master. It should now go through without an issue.

   <details>
   
   ```
   $ git push origin master
   ```
   
   </details>







