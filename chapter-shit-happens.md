# shit-happens

## 1. Restore a deleted file
```sh
git checkout essay
```

## 2. Restore a file from the past
```sh
git checkout HEAD~1 -- essay
git add .
git commit -m "restored good version"
```

## 3. Undo a bad commit
```sh
git reset HEAD~1
git add .
git commit -m "More numbers"
```

## 4. I pushed something broken
```sh
git revert HEAD~1
git push
```

## 5. Go back to where you were before
```sh
git reflog
git checkout HEAD~7
```