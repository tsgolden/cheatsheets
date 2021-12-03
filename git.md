# git

- Add remote repo to track: 

  ```sh
  git remote add origin git@github.com:<user>/<repo>.git
  ```

- Push to new upstream remote repo:

  ```sh
  git push -u origin master
  ```
- Delete last commit:

  ```sh
  git reset --hard HEAD^
  ```

- Delete last n commits:

  ```sh
  git reset --hard HEAD^n
  ```

