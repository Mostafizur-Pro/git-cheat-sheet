## Stashing

Store modified and staged changes (to include untracked files, add `-u` flag. For untracked & ignored files, add `-a`):

```bash
$ git stash
```

As above, but add a comment:

```bash
$ git stash save "comment"
```

Partial stash (stash just single file):

```bash
$ git stash push -p
```

List all stashes:

```bash
$ git stash list
```

Apply stash:

```bash
$ git stash apply stash@{1}
```

Delete stash at index 1 (omit stash@{n} to delete the last stash):

```bash
$ git stash drop stash@{1}
```

Clear all stashes:

```bash
$ git stash clear
```
