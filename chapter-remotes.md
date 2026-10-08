# remote

## 1. Friends
```bash
git pull
echo "Line 3, asdfa" >> essay
git add .
git commit -m 'add third line'
git push
git pull
echo "Line 5, asdfa" >> essay
git add.
git commit -m 'add fifth line'
git push
```


## 2. Problems
```bash
git add .
git commit -m 'commit local changes'
git pull
nano file
git add .
git commit -m 'made compromise'
git push
```
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
