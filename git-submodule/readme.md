# git submodule


https://www.cnblogs.com/xgqfrms/protected/p/12552884.html

```sh
$ git submodule add https://github.com/chaconinc/DbConnector

Cloning into 'DbConnector'...
remote: Counting objects: 11, done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 11 (delta 0), reused 11 (delta 0)
Unpacking objects: 100% (11/11), done.
Checking connectivity... done.

```

## `.gitmodules`

```.gitmodules
[submodule "DbConnector"]
	path = DbConnector
	url = https://github.com/chaconinc/DbConnector
```

https://git-scm.com/book/en/v2/Git-Tools-Submodules

https://git-scm.com/docs/git-submodule

***

## demo

```sh
# init
$ git submodule init

# clone
$ git submodule update

```

## better way

```sh
# clone --recursive
$ git clone --recursive https://github.com/xgqfrms/git-submodule

```
