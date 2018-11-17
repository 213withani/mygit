# everday git
```js
git pull
git status
git add .
git commit -m"Message to describe your commit."
git branch
git checkout master
git checkout my-branch
// run in your branch to merge what's on master to your local
git merge master 

// I used it to disregard my changes if I want to switch btwn branch and master.
git checkout -- . 
```
https://gist.github.com/arttuladhar/5887559

# git stash
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
