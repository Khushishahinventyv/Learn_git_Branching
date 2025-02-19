
## Level - 1 : Clone Intro

```bash
$ git clone
```
![alt text](image.png)


## Level - 2 : Remote Branches


```bash
$ git commit
$ git checkout o/main
$ git commit
```

![alt text](image-1.png)


## Level - 3 : 

```bash 
$ git fetch
```

![alt text](image-2.png)

## Level - 4 : Git pullin'

```bash
$ git pull
```
![alt text](image-3.png)

## Level - 5 : Faking Teamwork

```bash
$ git commit
$ git clone
local branch "main" set to track remote branch "o/main"
$ git fakeTeamwork main 1
$ git branch -f main c1
$ git commit
$ git fetch
$ git merge o/main
```

![alt text](image-4.png)

## Level - 6 : Git Pushin'
```bash
$ git commit
$ git commit
$ git push
```
![alt text](image-5.png)

## Level - 7 : Diverged History

```bash
$ git clone
local branch "main" set to track remote branch "o/main"
$ git fakeTeamwork
$ git fetch
$ git commit
$ git rebase o/main
$ git push
```

![alt text](image-6.png)


## Level - 8 : 

```bash
$ git checkout -b feature
$ git push
local branch "feature" set to track remote branch "o/feature"
$ git branch -f main c1
```

![alt text](image-7.png)