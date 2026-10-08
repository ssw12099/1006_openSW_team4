# Changing the past

## Rebasing

```
git checkout main
git reset --hard (baguette)
git rebase (coffe)
git rebase (donut)
```

## Reordering events

```sh
git checkout e097d2f # The Beginning
git cherry-pick ... # underwear
git cherry-pick ... # pants
git cherry-pick ... # shirt
git cherry-pick ... # shoes
git checkout main
git reset --hard ... #shoes
```
