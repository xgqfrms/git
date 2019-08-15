# git


```sh
# help
$ git --help
$ git help -a
$ git help -g


# pull
$ git pull

# check status
$ git status

# add
$ git add .
$ git add -A
$ git add --all

# commit
$ git commit -A m"commit comments information"

# push
$ git psuh

# log
$ git log


```


## git & configs


https://alvinalexander.com/git/git-show-change-username-email-address
https://stackoverflow.com/questions/7552054/git-cli-get-user-info-from-username


## github


https://help.github.com/articles/setting-your-username-in-git/
https://help.github.com/articles/setting-your-commit-email-address-in-git/

https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration


***

## git commands


```sh

$ git config user.name
$ git config user.email


```


```sh

xgqfrms@W10P-xgqfrms MINGW64 /e/Angular-2018 (master)
$ git config --list
core.symlinks=true
core.autocrlf=true
core.fscache=true
color.diff=auto
color.status=auto
color.branch=auto
color.interactive=true
help.format=html
rebase.autosquash=true
http.sslcainfo=H:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
http.sslbackend=openssl
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
credential.helper=manager
core.editor='H:\Microsoft VS Code\Code.exe' --wait
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/xgqfrms/Angular-2018.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.master.remote=origin
branch.master.merge=refs/heads/master

xgqfrms@W10P-xgqfrms MINGW64 /e/Angular-2018 (master)


$ git config
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-regex]
    --get-all             get all values: key [value-regex]
    --get-regexp          get values for regexp: name-regex [value-regex]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value_regex]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-regex]
    --unset-all           remove all matches: name [value-regex]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <>         value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --default <value>     with --get, use default value when missing entry


xgqfrms@W10P-xgqfrms MINGW64 /e/Angular-2018 (master)



```


```sh

$ git --help

$ git help -a
$ git help -g


```


```sh

xgqfrms@W10P-xgqfrms MINGW64 /e/Angular-2018 (master)
$ git --help
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.

xgqfrms@W10P-xgqfrms MINGW64 /e/Angular-2018 (master)


$ git help -g

The common Git guides are:
   attributes          Defining attributes per path
   cli                 Git command-line interface and conventions
   core-tutorial       A Git core tutorial for developers
   cvs-migration       Git for CVS users
   diffcore            Tweaking diff output
   everyday            A useful minimum set of commands for Everyday Git
   glossary            A Git Glossary
   hooks               Hooks used by Git
   ignore              Specifies intentionally untracked files to ignore
   modules             Defining submodule properties
   namespaces          Git namespaces
   repository-layout   Git Repository Layout
   revisions           Specifying revisions and ranges for Git
   tutorial            A tutorial introduction to Git
   tutorial-2          A tutorial introduction to Git: part two
   workflows           An overview of recommended workflows with Git

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.

xgqfrms@W10P-xgqfrms MINGW64 /e/Angular-2018 (master)




xgqfrms@W10P-xgqfrms MINGW64 /e/Angular-2018 (master)
$ git help -a
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

available git commands in 'H:/Program Files/Git/mingw64/libexec/git-core'

  add                     gc                      rebase--helper
  add--interactive        get-tar-commit-id       rebase--interactive
  am                      grep                    receive-pack
  annotate                gui                     reflog
  apply                   gui--askpass            remote
  archimport              gui--askyesno           remote-ext
  archive                 gui.tcl                 remote-fd
  askpass                 hash-object             remote-ftp
  bisect                  help                    remote-ftps
  bisect--helper          http-backend            remote-http
  blame                   http-fetch              remote-https
  branch                  http-push               repack
  bundle                  imap-send               replace
  cat-file                index-pack              request-pull
  check-attr              init                    rerere
  check-ignore            init-db                 reset
  check-mailmap           instaweb                rev-list
  check-ref-format        interpret-trailers      rev-parse
  checkout                legacy-rebase           revert
  checkout-index          legacy-stash            rm
  cherry                  log                     send-email
  cherry-pick             ls-files                send-pack
  citool                  ls-remote               serve
  clean                   ls-tree                 sh-i18n--envsubst
  clone                   mailinfo                shortlog
  column                  mailsplit               show
  commit                  merge                   show-branch
  commit-graph            merge-base              show-index
  commit-tree             merge-file              show-ref
  config                  merge-index             stage
  count-objects           merge-octopus           stash
  credential              merge-one-file          status
  credential-manager      merge-ours              stripspace
  credential-store        merge-recursive         submodule
  credential-wincred      merge-resolve           submodule--helper
  cvsexportcommit         merge-subtree           subtree
  cvsimport               merge-tree              svn
  cvsserver               mergetool               symbolic-ref
  daemon                  mktag                   tag
  describe                mktree                  unpack-file
  diff                    mv                      unpack-objects
  diff-files              name-rev                update
  diff-index              notes                   update-git-for-windows
  diff-tree               p4                      update-index
  difftool                pack-objects            update-ref
  difftool--helper        pack-redundant          update-server-info
  fast-export             pack-refs               upload-archive
  fast-import             patch-id                upload-pack
  fetch                   prune                   var
  fetch-pack              prune-packed            verify-commit
  filter-branch           pull                    verify-pack
  fmt-merge-msg           push                    verify-tag
  for-each-ref            quiltimport             web--browse
  format-patch            range-diff              whatchanged
  fsck                    read-tree               worktree
  fsck-objects            rebase                  write-tree

git commands available from elsewhere on your $PATH

  flow  lfs

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.

xgqfrms@W10P-xgqfrms MINGW64 /e/Angular-2018 (master)


```
