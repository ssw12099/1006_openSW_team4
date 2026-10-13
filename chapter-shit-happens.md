# Shit happends

## Restore a deleted file

```sh
git checkout ...(Initial commit)
git checkout main
```

## Restore a file from the past

```sh
git checkout HEAD~1 -- essay
git commit -am "restore good version"
```

## Undo a bad commit

```sh
git reset HEAD~1
git commit -am "More numbers"
```

## I pushed something broken

```sh
git revert HEAD~1
git push
```
