## Level - 1 : Push Main

```bash
$ git checkout main
$ git pull --rebase
$ git checkout side1
$ git rebase main
$ git checkout side2
$ git rebase side1
$ git checkout side3
$ git rebase side2
$ git checkout main
$ git rebase side3
$ git push
```
![alt text](image.png)

## Level - 2 
```bash
$ git pull
$ git checkout main
$ git pull
$ git merge side1
$ git merge side2
$ git merge side3
$ git push
```

![alt text](image-1.png)