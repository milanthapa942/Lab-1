$ git
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:
acuser@Macusers-MacBook-Pro Group1 % git branch -a
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
macuser@Macusers-MacBook-Pro Group1 % git branch group-01
macuser@Macusers-MacBook-Pro Group1 % git checkout group-01
Switched to branch 'group-01'
macuser@Macusers-MacBook-Pro Group1 % git branch
* group-01
  main
macuser@Macusers-MacBook-Pro Group1 % git log
commit b02a1a98a2cd4c4f7f8d81058a3f5e505e076192 (HEAD -> group-01, origin/main, origin/HEAD, main)
Author: naplyon3 <naplyon3@hotmail.com>
Date:   Thu Sep 3 14:16:18 2026 +0300

    Create ReadMe.md

commit 511e5bdfa096d333977468cb63f520f0108a4592
Author: Leo Li <leo.li@hamk.fi>
Date:   Tue Aug 25 13:30:52 2026 +0300

    update template notebook

commit 3b4512564ecdd149e340f78bf7b11a7b34bdc7b9
Author: Leo Li <leo.li@hamk.fi>
Date:   Tue Aug 25 13:25:59 2026 +0300

    add robotic engineering book template

commit 2f3be2e2d0a4094869a5d1cc4205a7397a798fc1
Author: Leo Li <leo.li@hamk.fi>
Date:   Tue Aug 25 12:49:43 2026 +0300

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

User@DESKTOP-8GJ0GBR MINGW64 /d/MyDoc/Bsc/FINLAND/Academics/Robotics/lab1 (main)
$ git branch -a
  DevSanz
* main
  remotes/origin/DevSanz
  remotes/origin/HEAD -> origin/main
  remotes/origin/main

User@DESKTOP-8GJ0GBR MINGW64 /d/MyDoc/Bsc/FINLAND/Academics/Robotics/lab1 (main)
$ git branch group 5
fatal: not a valid object name: '5'

User@DESKTOP-8GJ0GBR MINGW64 /d/MyDoc/Bsc/FINLAND/Academics/Robotics/lab1 (main)
$ git branch group-05

User@DESKTOP-8GJ0GBR MINGW64 /d/MyDoc/Bsc/FINLAND/Academics/Robotics/lab1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

User@DESKTOP-8GJ0GBR MINGW64 /d/MyDoc/Bsc/FINLAND/Academics/Robotics/lab1 (main)
$ git branch-group05
git: 'branch-group05' is not a git command. See 'git --help'.

User@DESKTOP-8GJ0GBR MINGW64 /d/MyDoc/Bsc/FINLAND/Academics/Robotics/lab1 (main)
$ git branch group-01

User@DESKTOP-8GJ0GBR MINGW64 /d/MyDoc/Bsc/FINLAND/Academics/Robotics/lab1 (main)
$ git checkout group-01
Switched to branch 'group-01'

User@DESKTOP-8GJ0GBR MINGW64 /d/MyDoc/Bsc/FINLAND/Academics/Robotics/lab1 (group-01)
$ git log
commit b95e8fae529dfe0fafd57d2096c975692d33b145 (HEAD -> group-01, origin/main, origin/HEAD, main, group-05)
Author: adittya dey <adittyadey168@gmail.com>
Date:   Thu Sep 3 17:20:11 2026 +0600

    Add Group 11

commit b02a1a98a2cd4c4f7f8d81058a3f5e505e076192 (origin/DevSanz, DevSanz)
Author: naplyon3 <naplyon3@hotmail.com>
Date:   Thu Sep 3 14:16:18 2026 +0300

    Create ReadMe.md
commit b95e8fae529dfe0fafd57d2096c975692d33b145 (HEAD -> group-01, origin/main, origin/HEAD, main, group-05)
Author: adittya dey <adittyadey168@gmail.com>
Date:   Thu Sep 3 17:20:11 2026 +0600

    Add Group 11

commit b02a1a98a2cd4c4f7f8d81058a3f5e505e076192 (origin/DevSanz, DevSanz)
Author: naplyon3 <naplyon3@hotmail.com>
Date:   Thu Sep 3 14:16:18 2026 +0300

    Create ReadMe.md
:
commit b95e8fae529dfe0fafd57d2096c975692d33b145 (HEAD -> group-01, origin/main, origin/HEAD, main, group-05)
Author: adittya dey <adittyadey168@gmail.com>
Date:   Thu Sep 3 17:20:11 2026 +0600

    Add Group 11

commit b02a1a98a2cd4c4f7f8d81058a3f5e505e076192 (origin/DevSanz, DevSanz)
Author: naplyon3 <naplyon3@hotmail.com>
Date:   Thu Sep 3 14:16:18 2026 +0300

    Create ReadMe.md
...skipping...
commit b95e8fae529dfe0fafd57d2096c975692d33b145 (HEAD -> group-01, origin/main, origin/HEAD, main, group-05)
Author: adittya dey <adittyadey168@gmail.com>
Date:   Thu Sep 3 17:20:11 2026 +0600

    Add Group 11

commit b02a1a98a2cd4c4f7f8d81058a3f5e505e076192 (origin/DevSanz, DevSanz)
Author: naplyon3 <naplyon3@hotmail.com>
Date:   Thu Sep 3 14:16:18 2026 +0300

    Create ReadMe.md

...skipping...
-05)
Author: adittya dey <adittyadey168@gmail.com>
Date:   Thu Sep 3 17:20:11 2026 +0600

    Add Group 11

commit b02a1a98a2cd4c4f7f8d81058a3f5e505e076192 (origin/DevSanz, DevSanz)
Author: naplyon3 <naplyon3@hotmail.com>
Date:   Thu Sep 3 14:16:18 2026 +0300

    Create ReadMe.md

commit 511e5bdfa096d333977468cb63f520f0108a4592

User@DESKTOP-8GJ0GBR MINGW64 /d/MyDoc/Bsc/FINLAND/Academics/Robotics/lab1 (group-01)
$ git
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

User@DESKTOP-8GJ0GBR MINGW64 /d/MyDoc/Bsc/FINLAND/Academics/Robotics/lab1 (group-01)
$ git log
commit b95e8fae529dfe0fafd57d2096c975692d33b145 (HEAD -> group-01, origin/main, origin/group-01, origin/HEAD, main, group-05)
Author: adittya dey <adittyadey168@gmail.com>
Date:   Thu Sep 3 17:20:11 2026 +0600

    Add Group 11

commit b02a1a98a2cd4c4f7f8d81058a3f5e505e076192 (origin/DevSanz, DevSanz)
Author: naplyon3 <naplyon3@hotmail.com>
Date:   Thu Sep 3 14:16:18 2026 +0300

    Create ReadMe.md

User@DESKTOP-8GJ0GBR MINGW64 /d/MyDoc/Bsc/FINLAND/Academics/Robotics/lab1 (group-01)
$ git remote -v
origin  https://github.com/ICT-Robotics26/lab1.git (fetch)
origin  https://github.com/ICT-Robotics26/lab1.git (push)

User@DESKTOP-8GJ0GBR MINGW64 /d/MyDoc/Bsc/FINLAND/Academics/Robotics/lab1 (group-01)
$ touch git-command.md
