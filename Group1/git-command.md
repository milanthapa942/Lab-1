 C:\Users\admin\OneDrive\Documents\GitHub\lab1> git branch -a
* main
  remotes/origin/DevSanz
  remotes/origin/HEAD -> origin/main
  remotes/origin/group-01
  remotes/origin/group-04
  remotes/origin/group-07
  remotes/origin/group-08
  remotes/origin/group-99
  remotes/origin/lab-12
  remotes/origin/main
PS C:\Users\admin\OneDrive\Documents\GitHub\lab1> git branch group01
PS C:\Users\admin\OneDrive\Documents\GitHub\lab1> git checkout group01
D       Group1/ReadMe.md
Switched to branch 'group01'
PS C:\Users\admin\OneDrive\Documents\GitHub\lab1> git log
commit 2a49c0a16c4b17231e3f7c3404e6e07c93abb0a3 (HEAD -> group01, origin/main, origin/HEAD, main)
Merge: f756062 8100640
Author: EFS <147025255+aRturS-qwert@users.noreply.github.com>
Date:   Thu Sep 3 15:07:33 2026 +0300

    Merge pull request #2 from ICT-Robotics26/group-04
    
    Added Git command results for group 04

commit f75606271fd8357ef78209f26e11d12b725d5f3b
Merge: a63f1b3 af25ac1
Author: PeterSabik2007 <amk1018730@student.hamk.fi>
Date:   Thu Sep 3 13:57:37 2026 +0200

    Merge pull request #3 from ICT-Robotics26/group-07
    
    Create git-command.md

commit a63f1b31ab23df30679a6a87832e52b94029b441
Merge: b95e8fa 3c06308
Author: Leo Li <leo.li@hamk.fi>
Date:   Thu Sep 3 14:56:05 2026 +0300

    Merge pull request #1 from ICT-Robotics26/group-99
    
    add git/command.md

commit 3c063084324e21c9e4a201627b7075c8fd2f266a (origin/group-99)
Author: Leo Li <leo.li@hamk.fi>
Date:   Thu Sep 3 14:53:47 2026 +0300

...skipping...
commit 2a49c0a16c4b17231e3f7c3404e6e07c93abb0a3 (HEAD -> group01, origin/main, origin/HEAD, main)
Merge: f756062 8100640
Author: EFS <147025255+aRturS-qwert@users.noreply.github.com>
Date:   Thu Sep 3 15:07:33 2026 +0300

    Merge pull request #2 from ICT-Robotics26/group-04
    
    Added Git command results for group 04

commit f75606271fd8357ef78209f26e11d12b725d5f3b
Merge: a63f1b3 af25ac1
Author: PeterSabik2007 <amk1018730@student.hamk.fi>
Date:   Thu Sep 3 13:57:37 2026 +0200

    Merge pull request #3 from ICT-Robotics26/group-07
    
    Create git-command.md

commit a63f1b31ab23df30679a6a87832e52b94029b441
Merge: b95e8fa 3c06308
Author: Leo Li <leo.li@hamk.fi>
Date:   Thu Sep 3 14:56:05 2026 +0300

    Merge pull request #1 from ICT-Robotics26/group-99
    
    add git/command.md

commit 3c063084324e21c9e4a201627b7075c8fd2f266a (origin/group-99)
Author: Leo Li <leo.li@hamk.fi>
Date:   Thu Sep 3 14:53:47 2026 +0300

    add git/command.md
...skipping...
n/HEAD, main)
Merge: f756062 8100640
Author: EFS <147025255+aRturS-qwert@users.noreply.github.com>
Date:   Thu Sep 3 15:07:33 2026 +0300

    Merge pull request #2 from ICT-Robotics26/group-04
    
    Added Git command results for group 04

commit f75606271fd8357ef78209f26e11d12b725d5f3b
Merge: a63f1b3 af25ac1
Author: PeterSabik2007 <amk1018730@student.hamk.fi>
Date:   Thu Sep 3 13:57:37 2026 +0200

    Merge pull request #3 from ICT-Robotics26/group-07
    
    Create git-command.md

commit a63f1b31ab23df30679a6a87832e52b94029b441
Merge: b95e8fa 3c06308
Author: Leo Li <leo.li@hamk.fi>
Date:   Thu Sep 3 14:56:05 2026 +0300

    Merge pull request #1 from ICT-Robotics26/group-99
    
    add git/command.md

commit 3c063084324e21c9e4a201627b7075c8fd2f266a (origin/group-99)
Author: Leo Li <leo.li@hamk.fi>
Date:   Thu Sep 3 14:53:47 2026 +0300

    add git/command.md
PS C:\Users\admin\OneDrive\Documents\GitHub\lab1> git remote -v
origin  https://github.com/ICT-Robotics26/lab1.git (fetch)
origin  https://github.com/ICT-Robotics26/lab1.git (push)
PS C:\Users\admin\OneDrive\Documents\GitHub\lab1> git stauts
git: 'stauts' is not a git command. See 'git --help'.

The most similar command is
        status
PS C:\Users\admin\OneDrive\Documents\GitHub\lab1> git status
On branch group01
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    Group1/ReadMe.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Group1/git-command.md

no changes added to commit (use "git add" and/or "git commit -a")