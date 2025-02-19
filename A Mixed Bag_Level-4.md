# A Mixed Bag

## 1: Grabbing Just 1 Commit

### Commands

```
git checkout main
git cherry-pick c4
```

![alt text](./images/Screenshot%202025-02-18%20190005.png)

## 2: Juggling Commits

### Commands

```
git rebase -i HEAD~2
git rebase -i HEAD~1
git rebase -i HEAD~2
git branch -f main c3''
```

![alt text](./images/Screenshot%202025-02-19%20102343.png)

## 3: Juggling Commits #2

### Commands

```
git checkout main
git cherry-pick c2
git branch -f main c3
git rabase -i HEAD~2
```

![alt text](./images/Screenshot%202025-02-19%20103101.png)

## 4: Git Tags

### Commands

```
git tag v1 c2
git tag v0 c1
git checkout side^
```

![alt text](./images/Screenshot%202025-02-19%20104209.png)

## 5: Git Describe

### Commands

```
git commit
```

![alt text](./images/Screenshot%202025-02-19%20104525.png)
