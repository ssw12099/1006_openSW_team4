# Remotes

## Friend

```sh
git pull
```

```essay
3+|Line 3
```

```sh
git add essay
git commit -m "add line 3"
git push
git pull
```

```essay
5+|Line 5
```

```sh
git add essay
git commit -m "add line 5"
git push
```

## Problems

```sh
git pull

git add file
git commit -m "local changes"

git merge /refs/remotes/friend/main
```

```file
The bikeshed should be blue+green
```

```sh
git add file
git commit -m "Merge remote-tracking branch 'refs/remotes/friend/main' into main"
git push
```
