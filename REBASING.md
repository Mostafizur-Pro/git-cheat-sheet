## Rebasing

Rebase feature branch onto main to incorporate new changes made to main (prevents unnecessary merge commits into feature, keeping history linear):

```bash
$ git checkout feature
$ git rebase main
```

Iteratively clean up a branch's commits before rebasing onto main:

```bash
$ git rebase -i main
```

Iteratively rebase the last 3 commits in the current branch:

```bash
$ git rebase -i Head~3
```
