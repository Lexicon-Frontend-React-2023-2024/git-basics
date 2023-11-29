## Git Basics

Git add will tell git to start tracking the changes, and prepare it for commit. All changed files in your project will be detected by git, but if you want to commit these changes to your local repo you must first add them to the "staged" area. Here all the changes are that will soon be commited.

```
git add
```

Git commit takes a snapshot of our changes in the staged area and saves it as a version of our code in our local repo. This makes it possible to go back to previous versions of the code if we have to.

```
git commit
```

Git push is used when we want to push our recent version, snapshot, to our remote repo up on github. This makes the code available to other developers.

```
git push
```

Git pull is the opposite to git push basically. It pulls down the current version from the remote repo to our local repo on our computer.

```
git pull
```

Git status checks the status of the files that have been changed or not changed.

```
git status
```

Git log gives you a list of the recent commit history.

```
git log
```
