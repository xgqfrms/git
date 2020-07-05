# git remote

https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes

https://git-scm.com/docs/git-remote

```sh
# git remote [-v | --verbose]
# git remote add [-t <branch>] [-m <master>] [-f] [--[no-]tags] [--mirror=<fetch|push>] <name> <url>
# git remote rename <old> <new>
# git remote remove <name>
# git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
# git remote set-branches [--add] <name> <branch>…​
# git remote get-url [--push] [--all] <name>
# git remote set-url [--push] <name> <newurl> [<oldurl>]
# git remote set-url --add [--push] <name> <newurl>
# git remote set-url --delete [--push] <name> <url>
# git remote [-v | --verbose] show [-n] <name>…​
# git remote prune [-n | --dry-run] <name>…​
# git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)…​]

```

## git remote add


https://www.atlassian.com/git/tutorials/syncing

https://docs.github.com/en/github/using-git/adding-a-remote

```sh
$ git remote add origin https://github.com/user/repo.git
# Set a new remote

$ git remote -v
# Verify new remote
> origin  https://github.com/user/repo.git (fetch)
> origin  https://github.com/user/repo.git (push)

```


https://stackoverflow.com/questions/42830557/git-remote-add-origin-vs-remote-set-url-origin

```sh
$ git remote add origin git@github.com:User/UserRepo.git

$ git push -u origin master
```
