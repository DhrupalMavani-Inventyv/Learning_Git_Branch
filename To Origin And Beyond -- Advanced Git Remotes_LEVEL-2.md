# To Origin And Beyond -- Advanced Git Remotes!

## 1 Push Main!

### Commands

```
git checkout main
git pull --rebase
git checkout side1
git rebase main
git checkout side2
git rebase side2
git checkout side3
git rebase side2
git checkout main
git rebase side3
git push
```

![alt text](./images/Screenshot%202025-02-19%20183447.png)

## 2 Merging with remotes

### Commands

```
git checkout main
git pull --rebase
git merge side1
git merge side2
git merge side3
git push
```

![alt text](./images/Screenshot%202025-02-20%20101715.png)

## 3 Remote Tracking

### Commands

```
git checkout -b side o/main
git commit
git pull --rebase
git push
```

![alt text](./images/Screenshot%202025-02-20%20104626.png)

## 4 Git push arguments

### Commands

```
git push origin main
git push origin foo
```

![alt text](./images/Screenshot%202025-02-20%20105133.png)

## 5 Git push arguments -- Expanded!

### Commands

```
git push origin foo:main
git push origin main^:foo
```

![alt text](./images/Screenshot%202025-02-20%20105628.png)

## 6 Fetch arguments

### Commands

```
git fetch origin c3:foo
git fetch origin c6:main
git checkout foo
git merge main
```

![alt text](./images/Screenshot%202025-02-20%20110646.png)

## 7 Source of nothing

### Commands

```
git push origin :foo
git fetch origin :bar
```

![alt text](./images/Screenshot%202025-02-20%20111011.png)

## 8 Pull arguments

### Commands

```
git pull origin c3:foo
git pull origin c2:side
```

![alt text](./images/Screenshot%202025-02-20%20113130.png)
