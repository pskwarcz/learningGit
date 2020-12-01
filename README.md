# learning Git

### commands
```
git init
git remote add origin https://github.com/pskwarcz/learningGit.git
git push -u origin master
git push
git pull origin master
git add filenameOrChangesToAdd
git diff
git checkout -- filename
```
### branch
```
git branch clean_up 
git checkout clean_up     -select current branch:wq
git merge clean_up
git branch -d branch-name  -removes branch
```

```git pull``` is essentially a ```git fetch``` immediately followed by ```git merge```

Prune all unreachable objects from the object database:
```git remote prune origin```

