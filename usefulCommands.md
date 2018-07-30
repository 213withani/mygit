```js
git status
git pull
git add .
git commit -m"Message to describe your commit."
git merge master // run in your branch to merge what's on master to your local

```


https://stackoverflow.com/questions/19003009/how-to-recover-stashed-uncommitted-changes

```js
git stash apply
git stash drop to get rid of it

```

# How to fix committing to the wrong Git branch?
## If you haven't yet pushed your changes, you can also do a soft reset:
```js
git reset --soft HEAD^

```
https://stackoverflow.com/questions/2941517/how-to-fix-committing-to-the-wrong-git-branch
