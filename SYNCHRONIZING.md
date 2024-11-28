## Synchronizing

Add a remote repo:

```bash
$ git remote add <alias> <url>
```

View all remote connections (add `-v` to view full URLs):

```bash
$ git remote
```

Remove a connection:

```bash
$ git remote remove <alias>
```

Rename a connection:

```bash
$ git remote rename <old> <new>
```

Fetch all branches from remote repo (no merge):

```bash
$ git fetch <alias>
```

Fetch a specific branch:

```bash
$ git fetch <alias> <branch>
```

Merge fetched changes into current branch:

```bash
$ git pull
```

Push all branches to remote repo:

```bash
$ git push <alias> <branch>
```
