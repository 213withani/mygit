# Cherry picks
```
   git pull
   git fetch
   git checkout V1.76.0
   git pull
   git fetch
   git cherry-pick -n 7049ec9
   git cherry-pick -n 4152fe8
   git status
   git checkout -b NAV-950-RB
   git status
   git commit -m"NAV-950 Cherry pick team spend amount fix."
   git push origin NAV-950-RB
```

# Checkout branch from remote origin aka from github
~/Documents/dev/silver (master ✔) ᐅ git checkout origin/FEATURE-B
Note: checking out 'origin/FEATURE-B'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 28303a1 NAV-848 Added dropdown UI and cleaned view as user search box container..
~/Documents/dev/folder (28303a1 ✔) ᐅ git checkout -b FEATURE-B

# How to get a repo and start working
```git clone repoName
cd into folder
npm i
npm start
```

# Remove a folder that is not empty
## Be Careful when using command
```rm -fr folderName```

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

# Reset your local master branch to be the same as origin
```git reset --hard origin/master```
https://stackoverflow.com/questions/15432052/what-is-the-meaning-of-git-reset-hard-origin-master
