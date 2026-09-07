PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> cd ..
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu> cd lab1
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> dir


    Directory: C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1


Mode                 LastWriteTime         Length Name                                                                           
----                 -------------         ------ ----                                                                           
d-----          9/7/2026   9:34 AM                99                                                                             
d-----          9/6/2026  10:23 PM                group-06                                                                       
d-----          9/3/2026   2:17 PM                Group1                                                                         


PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> dir group-06


    Directory: C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1\group-06


Mode                 LastWriteTime         Length Name                                                                           
----                 -------------         ------ ----                                                                           
-a----          9/6/2026  10:59 PM           4791 git-command.md                                                                 


PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> git branch -a
* group-06
  main
  remotes/origin/DevSanz
  remotes/origin/HEAD -> origin/main
  remotes/origin/group-01
  remotes/origin/group-04
  remotes/origin/group-06
  remotes/origin/group-07
  remotes/origin/group-08
  remotes/origin/group-11
  remotes/origin/group-99
  remotes/origin/group01
  remotes/origin/lab-12
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> git branch group-06
fatal: a branch named 'group-06' already exists
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> git checkout group-06
D       99/group-06/git-command.md
Already on 'group-06'
Your branch and 'origin/group-06' have diverged,
and have 1 and 1 different commits each, respectively.
  (use "git pull" if you want to integrate the remote branch with yours)
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> git log
commit 5ddc7ee59b32c4839eef058b18f87ad5c270a8b1 (HEAD -> group-06)
Author: Sanduni Sumanasena <sandunisumanasena@gmail.com>
Date:   Mon Sep 7 10:30:13 2026 +0300

    Add Git command result for group 06

commit b84cd3012a65f50121015aebd52eab3e7b625a6d
Author: Sanduni Sumanasena <sandunisumanasena@gmail.com>
Date:   Sun Sep 6 23:03:30 2026 +0300

    Add Git command result for group 06

commit dcad0463b051c0818106ccc93b5d845f83f3c283
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> git remote -v
origin  https://github.com/ICT-Robotics26/lab1.git (fetch)
origin  https://github.com/ICT-Robotics26/lab1.git (push)
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> 