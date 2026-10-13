# shit-happens

## 1. Restore a deleted file
```sh
git checkout essay
```


## 2. Restore a file from the past
```sh
git checkout [commit] essay
git add .
git commit -m "restored good version"
```
[commit] 부분은 원하는 commit 부분을 우클릭한다. 지금의 경우 Initial commit 블록을 우클릭.

## 3. Undo a bad commit
```sh
git reset [commit]
git add .
git commit -m "More numbers"
```
More numberrrrrs commit 리셋, numbers 파일 수정, More numbers로 다시 커밋 

## I pushed something broken
```sh
git revert HEAD~1
git push
```

## 5. Go back to where you were before
```sh

```