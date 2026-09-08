# Git brach -a

PS C:\Users\s1734\Documents\GitHub\lab1> git branch -a
  fix-bug-1
* main
  remotes/origin/DevSanz
  remotes/origin/HEAD -> origin/main
  remotes/origin/main

nothing to commit, working tree clean
PS C:\Users\s1734\Documents\GitHub\lab1> git 
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
PS C:\Users\s1734\Documents\GitHub\lab1> ^C
PS C:\Users\s1734\Documents\GitHub\lab1> 
PS C:\Users\s1734\Documents\GitHub\lab1> git branch -a
  fix-bug-1
* main
  remotes/origin/DevSanz
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
PS C:\Users\s1734\Documents\GitHub\lab1>  
PS C:\Users\s1734\Documents\GitHub\lab1> git branch -a
  fix-bug-1
* main
  remotes/origin/DevSanz
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
PS C:\Users\s1734\Documents\GitHub\lab1> git branch group-99
PS C:\Users\s1734\Documents\GitHub\lab1> git branch -a      
  fix-bug-1
  group-99
* main
  remotes/origin/DevSanz
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
PS C:\Users\s1734\Documents\GitHub\lab1> git checkout group-99
Switched to branch 'group-99'
PS C:\Users\s1734\Documents\GitHub\lab1> git branch -a        
  fix-bug-1
* group-99
  main
  remotes/origin/DevSanz
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
PS C:\Users\s1734\Documents\GitHub\lab1> git log 
commit b02a1a98a2cd4c4f7f8d81058a3f5e505e076192 (HEAD -> group-99, origin/main, origin/HEAD, origin/DevSanz, main)
Author: naplyon3 <naplyon3@hotmail.com>
Date:   Thu Sep 3 14:16:18 2026 +0300

    Create ReadMe.md

commit 511e5bdfa096d333977468cb63f520f0108a4592 (fix-bug-1)
Author: Leo Li <leo.li@hamk.fi>
Date:   Tue Aug 25 13:30:52 2026 +0300

    update template notebook

commit 3b4512564ecdd149e340f78bf7b11a7b34bdc7b9
Author: Leo Li <leo.li@hamk.fi>
Date:   Tue Aug 25 13:25:59 2026 +0300
PS C:\Users\s1734\Documents\GitHub\lab1> git remote -v
origin  https://github.com/ICT-Robotics26/lab1.git (fetch)
origin  https://github.com/ICT-Robotics26/lab1.git (push)