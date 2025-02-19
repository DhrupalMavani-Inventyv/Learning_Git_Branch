# Ramping Up

## 1: Detach yo' HEAD

### Commands

```
show goal

git checkout c4
```

![alt text](./images/Screenshot%202025-02-18%20182055.png)

## 2: Relative Refs (^)

### Commands

```
show goal

git checkout bugFix^
```

![alt text](./images/image-6.png)

## 3: Relative Refs #2 (~)

### Commands

```
git branch -f main c6

git checkout HEAD^1

git bbranch -f bugFix HEAD~1

git branch -f bugFix HEAD~1
```

![alt text](./images/Screenshot%202025-02-18%20183332.png)

## 4: Reversing Changes in Git

### Commands

```
git reset HEAD^1

git checkout pushed

git revert pushed
```

![alt text](./images/Screenshot%202025-02-18%20183619.png)
