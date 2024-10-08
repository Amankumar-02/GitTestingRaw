to open vs code from file explorer ==> top search cmd ==> code .

to initialize the git
-- to open/run a file ==> code fileName

1. inside the directory initialize the git local repo == git init
2. to show which file is not added to git / staging area == git status
3. add / push the file == git add fileName //or// add all == git add .
4. remove file == git rm fileName
5. adding commit == git commit -m "message"
6. to read the recent commit == git log 
7. when file modify first == git add then == git commit -m "message"
8. check the diff in added and modified file == git diff fileName
9. to restore the last saved file data == git checkout fileName

10. link the github/remoteRepo with the local directory to push the code == git remote add origin (repo url)
11. git branch -M main
12. now push the code == git push -u origin main

13. add a clone repo to local == git clone (url)

14. create a new branch in local repo == git branch branchName
15. read the existing branches == git branch
16. switching b/w branches == git checkout branchName

17. merge the branches == inside main branch code == git merge branchName
18. add only branch to remote repo == same previous steps with newBranch == git push -u origin branchName







usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.