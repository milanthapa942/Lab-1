PS C:\Users\khadk\OneDrive\Documents\GitHub\lab1> git branch -a
  group-05
* main
  remotes/origin/DevSanz
  remotes/origin/GROUP-13
  remotes/origin/Group_10
  remotes/origin/HEAD -> origin/main
  remotes/origin/fix-wrong-items
  remotes/origin/group-01
  remotes/origin/group-04
  remotes/origin/group-05
:## git branch group-05
fatal: a branch named 'group-05' already exists

## git checkout group-05
Switched to branch 'group-05'
Your branch is up to date with 'origin/group-05'.

## git log
commit a63f1b31ab23df30679a6a87832e52b94029b441 (HEAD -> group-05, origin/group-05)
Merge: b95e8fa 3c06308
Author: Leo Li <leo.li@hamk.fi>
Date:   Thu Sep 3 14:56:05 2026 +0300

    Merge pull request #1 from ICT-Robotics26/group-99
    add git/command.md

commit 3c063084324e21c9e4a201627b7075c8fd2f266a (origin/group-99)
(...earlier commit history)

## git remote -v
origin  https://github.com/ICT-Robotics26/lab1.git (fetch)
origin  https://github.com/ICT-Robotics26/lab1.git (push)