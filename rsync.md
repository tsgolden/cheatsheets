# rsync

- Execute a dry run: `--dry-run` or `-n`

- Increase verbosity: `-v`, `-vv`, etc.

- Sync up two directories, making one (`dst`) a mirror of the other (`src`):

  ```sh
  rsync -a src/ dst
  ```

  The trailing `/` is important and results in copying just the contents of `src` into `dst` rather than the directory itself. From [this SO answer](https://unix.stackexchange.com/a/178095).
