## Branches

List all local branches (add `-r` flag to show all remote branches, `-a` to show all branches):

```bash
$ git branch
```

Create a new branch:

```bash
$ git branch <new-branch>
```

Switch to a branch and update the working directory:

```bash
$ git checkout <branch>
```

Create a new branch and switch to it:

```bash
$ git checkout -b <new-branch>
```

Delete a merged branch:

```bash
$ git branch -d <branch>
```

Delete a branch, whether merged or not:

```bash
$ git branch -D <branch>
```

Add a tag to current commit (use `-a` to tag new releases):

```bash
$ git tag <tag-name>
```
