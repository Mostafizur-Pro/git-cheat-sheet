## Undoing Things

Move (and/or rename) a file and stage it:

```bash
$ git mv <existing-path> <new-path>
```

Remove a file from the working directory and from staging area, then stage the deletion:

```bash
$ git rm <file>
```

Reset a file or a commit:

- Reset a file from staging area only:
  ```bash
  $ git reset <file>
  ```
- Reset the index and working directory to a specific commit (read-only):
  ```bash
  $ git reset --hard <commit_ID>
  ```

Revert a commit by creating a new commit:

```bash
$ git revert <commit_ID>
```

Restore file to a specific commit (leaves staging alone):

```bash
$ git checkout <commit_ID> <file>
```
