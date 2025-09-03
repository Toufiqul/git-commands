### Merge branch with main

```
git checkout master
git pull origin master
git merge test
git push origin master
```


This will remove all uncommitted changes, even if staged,
and then pull:

```
git reset --hard HEAD
git pull
```