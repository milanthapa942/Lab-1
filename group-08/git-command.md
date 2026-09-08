PS C:\Users\vaish\Documents\GitHub\lab1> git branch -a 
* main
  remotes/origin/DevSanz
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
  PS C:\Users\vaish\Documents\GitHub\lab1> git branch -a fix-bug-1
fatal: the -a, and -r, options to 'git branch' do not take a branch name.
Did you mean to use: -a|-r --list <pattern>?  
PS C:\Users\vaish\Documents\GitHub\lab1> git checkout group-08
Switched to branch 'group-08'
PS C:\Users\vaish\Documents\GitHub\lab1> git log
commit b95e8fae529dfe0fafd57d2096c975692d33b145 (HEAD -> group-08, origin/main, origin/HEAD, main, group-8)
Author: adittya dey <adittyadey168@gmail.com>
Date:   Thu Sep 3 17:20:11 2026 +0600

    Add Group 11

commit b02a1a98a2cd4c4f7f8d81058a3f5e505e076192 (origin/DevSanz)
Author: naplyon3 <naplyon3@hotmail.com>
Date:   Thu Sep 3 14:16:18 2026 +0300
    Create ReadMe.md

commit 511e5bdfa096d333977468cb63f520f0108a4592
Author: Leo Li <leo.li@hamk.fi>
Date:   Tue Aug 25 13:30:52 2026 +0300

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
PS C:\Users\vaish\Documents\GitHub\lab1> git remote -v
origin  https://github.com/ICT-Robotics26/lab1.git (fetch)
origin  https://github.com/ICT-Robotics26/lab1.git (push)
PS C:\Users\vaish\Documents\GitHub\lab1> 
