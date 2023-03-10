#  `git branch` --remotes / --remote / -r

```sh
# alias
$ git branch -r

$ git branch --remotes

# typo 兼容 ✅
$ git branch --remote

```

![image](https://img2023.cnblogs.com/blog/740516/202303/740516-20230310224314749-1660245780.gif)


```sh
$ git branch --remote
# OR
$ git branch --remotes
# OR
$ git branch -r
```

https://github.com/xgqfrms/git/tree/master/git%20branch#git-remote

```sh
git branch [--color[=<when>] | --no-color] [--show-current]
	[-v [--abbrev=<n> | --no-abbrev]]
	[--column[=<options>] | --no-column] [--sort=<key>]
	[--merged [<commit>]] [--no-merged [<commit>]]
	[--contains [<commit>]] [--no-contains [<commit>]]
	[--points-at <object>] [--format=<format>]
	[(-r | --remotes) | (-a | --all)]
	[--list] [<pattern>…​]
git branch [--track[=(direct|inherit)] | --no-track] [-f]
	[--recurse-submodules] <branchname> [<start-point>]
git branch (--set-upstream-to=<upstream> | -u <upstream>) [<branchname>]
git branch --unset-upstream [<branchname>]
git branch (-m | -M) [<oldbranch>] <newbranch>
git branch (-c | -C) [<oldbranch>] <newbranch>
git branch (-d | -D) [-r] <branchname>…​
git branch --edit-description [<branchname>]
```

```sh
$ git branch -l

# -r causes the remote-tracking branches to be listed
$ git branch -r
$ git branch -lr

# -a shows both local and remote branches
$ git branch -a
$ git branch -la

```

https://git-scm.com/docs/git-branch
