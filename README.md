# problem

```sh
➜ git branch | wc -l
      325
```

# git-trash

![trash](/trash.png?raw=true "trash")

By default the current branch along with the branches `master`, `develop` and
`development` will be ignored. The current branch and `master` can never be
trashed but you can customize other or additional branches to ignore by setting
`SKIP_BRANCHES`.

```sh
➜ SKIP_BRANCHES="branch-1|feature/v3" git-trash
```
