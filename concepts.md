# Merging vs. Rebasing
https://www.atlassian.com/git/tutorials/merging-vs-rebasing

Both of these commands are designed to integrate changes from one branch into another branch—they just do it in very different ways.

My case:
``` git merge master ``` took master and merged it to my branch. I had the commit in master added to my branch. I had my branch behind master, commits I needed were at the top of master but with this command, master commits were added to my branch. 
