# Instructions for the Git Workshop

1. Git Config
- Walk through students
  ```
  git config user.name JohnDoe123
  git config user.email doejo@mnstate.edu
  ```
  
2. Git Clone
- Walk through students
    ```
    git clone https://github.com/MSUM-ACM/ACMGitWorkshop.git
    ```

3. Git Branch
- Theory Talk
    ```
    git branch bugfix/TestFix
    ```
4. Demo bug fix
- Walk through the standard procedure
    1. Review Quality Assurance Ticket
    2. Reproduce locally
    3. Remedy error
    4. Put new code on the repository
    ```
    git add *
    git commit -m "Fixed Ticket #372"
    git push
    ```
    
5. Students repeat demo
    - Students Branch
    ```
    git branch yourNameHere
    ```
    
    - Students add a line
    ```cs
    Console.WriteLine("yourNameHere");
    ```
    - Students Push to repository
    ```
    git add *
    git commit -m "Added yourNameHere to the file"
    git push --set-upstream origin yourNameHere
    ```
    - Go through Pull Requests
    - Merging back into dev
    - "tested by QA"
    - Merge into release
    - Merge into master

6. [First hand proof of field usage](https://github.com/journeyapps/zxing-android-embedded/network)