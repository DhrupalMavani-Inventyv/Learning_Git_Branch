# level 4 - A Mixed Bag

## 1: Grabbing Just 1 Commit

### Commands

```
git checkout main
git cherry-pick c4
```

![alt text](<Screenshot 2025-02-18 190005.png>)

## 2: Juggling Commits

### Commands

```
git rebase -i HEAD~2
git rebase -i HEAD~1
git rebase -i HEAD~2
git branch -f main c3''
```

![alt text](<Screenshot 2025-02-19 102343.png>)

## 3: Juggling Commits #2

### Commands

```
git checkout main
git cherry-pick c2
git branch -f main c3
git rabase -i HEAD~2
```

![alt text](<Screenshot 2025-02-19 103101.png>)

## 4: Git Tags

### Commands

```
git tag v1 c2
git tag v0 c1
git checkout side^
```

![alt text](<Screenshot 2025-02-19 104209.png>)

## 5: Git Describe

### Commands

```
git commit
```

![alt text](<Screenshot 2025-02-19 104525.png>)
