# Git Commands - Group 11

## 1. git branch -a

Command:

git branch -a

Output:
 group-01
* group-11
  main
  remotes/origin/DevSanz
  remotes/origin/HEAD -> origin/main
  remotes/origin/group-01
  remotes/origin/group-04
  remotes/origin/group-07

## 2. git branch group-11

Command:

git branch group-11

Output:
fatal: a branch named 'group-11' already exists

## 3. git checkout group-11

Command:

git checkout group-11

Output:
D       Group 11
D       Group1/ReadMe.md
D       Group1/git-command.md
Already on 'group-11'
Your branch is up to date with 'origin/group-11'.

## 4. git log

Command:

git log

Output:
commit fef9fdc5966f690d290dad09a105e08d1cf4bcef (HEAD -> group-11, origin/main, origin/group-11, origin/HEAD, main)
Merge: 2a49c0a 80e6920
Author: naplyon3 <55854451+naplyon3@users.noreply.github.com>
Date:   Thu Sep 3 21:53:25 2026 +0300

    Merge pull request #4 from ICT-Robotics26/group01
    
## 5. git remote -v

Command:

git remote -v

Output:
origin  https://github.com/ICT-Robotics26/lab1.git (fetch)
origin  https://github.com/ICT-Robotics26/lab1.git (push)
