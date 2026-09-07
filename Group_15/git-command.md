PS C:\Users\Khairul\OneDrive\Documents\GitHub\lab1> 
 *  History restored 

PS C:\Users\Khairul\OneDrive\Documents\GitHub\lab1> git
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the 
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ git
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\Khairul\OneDrive\Documents\GitHub\lab1> git
git : The term 'git' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the 
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ git
+ ~~~
    + CategoryInfo          : ObjectNotFound: (git:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS C:\Users\Khairul\OneDrive\Documents\GitHub\lab1> 
 *  History restored 

PS C:\Users\Khairul\OneDrive\Documents\GitHub\lab1> git
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   restore    Restore working tree files
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   diff       Show changes between commits, commit and working tree, etc
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   backfill   Download missing objects in a partial clone
   branch     List, create, or delete branches
   commit     Record changes to the repository
   history    EXPERIMENTAL: Rewrite history
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   reset      Set `HEAD` or the index to a known state
   switch     Switch branches
   tag        Create, list, delete or verify tags

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
PS C:\Users\Khairul\OneDrive\Documents\GitHub\lab1> 
 *  History restored 

PS C:\Users\Khairul\OneDrive\Documents\GitHub\lab1> git
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   restore    Restore working tree files
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   diff       Show changes between commits, commit and working tree, etc
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   backfill   Download missing objects in a partial clone
   branch     List, create, or delete branches
   commit     Record changes to the repository
   history    EXPERIMENTAL: Rewrite history
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   reset      Set `HEAD` or the index to a known state
   switch     Switch branches
   tag        Create, list, delete or verify tags

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
PS C:\Users\Khairul\OneDrive\Documents\GitHub\lab1> git branch -a
  DevSanz
* Group_15
  main
  remotes/origin/DevSanz
  remotes/origin/HEAD -> origin/main
  remotes/origin/group-01
  remotes/origin/group-04
  remotes/origin/group-06
  remotes/origin/group-07
  remotes/origin/group-08
PS C:\Users\Khairul\OneDrive\Documents\GitHub\lab1> git branch group_15
fatal: a branch named 'group_15' already exists
PS C:\Users\Khairul\OneDrive\Documents\GitHub\lab1> git checkout group_15
Switched to branch 'group_15'
PS C:\Users\Khairul\OneDrive\Documents\GitHub\lab1> git log
commit 0a089298270986ab5a93542ae76e36c353240716 (HEAD, origin/main, origin/HEAD, main, Group_15)
Merge: 74b86c6 322683b
Author: caroin-bit <camilla.roinevirta@gmail.com>
Date:   Mon Sep 7 11:11:50 2026 +0300

    Merge pull request #11 from ICT-Robotics26/group-04
    
    Group 04 - Reviewed and merged

commit 322683bf47be3bd6d210d8185cd0994b626f077b (origin/group-04)
PS C:\Users\Khairul\OneDrive\Documents\GitHub\lab1> git log
commit 0a089298270986ab5a93542ae76e36c353240716 (HEAD, origin/main, origin/HEAD, main, Group_15)
Merge: 74b86c6 322683b
Author: caroin-bit <camilla.roinevirta@gmail.com>
Date:   Mon Sep 7 11:11:50 2026 +0300

    Merge pull request #11 from ICT-Robotics26/group-04
    
    Group 04 - Reviewed and merged

commit 322683bf47be3bd6d210d8185cd0994b626f077b (origin/group-04)
PS C:\Users\Khairul\OneDrive\Documents\GitHub\lab1> git remote -v
origin  https://github.com/ICT-Robotics26/lab1.git (fetch)
origin  https://github.com/ICT-Robotics26/lab1.git (push)