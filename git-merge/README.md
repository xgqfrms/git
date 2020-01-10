# git merge all in one

> you can follow below steps

## 1. merge origin/master branch to feature branch

```sh
# step1: change branch to master, and pull to update all commits
$ git checkout master
$ git pull

# step2: change branch to target, and pull to update commits
$ git checkout feature
$ git pull

# step3: merge master to feature(⚠️ current is feature branch)
$ git merge master
```

## 2. merge feature branch to origin/master branch

```sh
$ git checkout master
$ git pull origin master

$ git merge feature
$ git push origin master

```

***

https://github.com/xgqfrms/git

https://stackoverflow.com/questions/16955980/git-merge-master-into-feature-branch/58814036#58814036

***



