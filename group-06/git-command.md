PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> git branch -a                  
* group-06
  main
  remotes/origin/DevSanz
  remotes/origin/HEAD -> origin/main
  remotes/origin/group-01
  remotes/origin/group-04
  remotes/origin/group-07
  remotes/origin/group-08
  remotes/origin/group-11
  remotes/origin/group-99
  remotes/origin/group01
  remotes/origin/lab-12
  remotes/origin/main
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> git branch group-06            
fatal: a branch named 'group-06' already exists
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> git checkout group-06          
Already on 'group-06'
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> git log                        
commit b02a1a98a2cd4c4f7f8d81058a3f5e505e076192 (HEAD -> group-06, origin/DevSanz, main)
Author: naplyon3 <naplyon3@hotmail.com>
Date:   Thu Sep 3 14:16:18 2026 +0300

    Create ReadMe.md

commit 511e5bdfa096d333977468cb63f520f0108a4592
Author: Leo Li <leo.li@hamk.fi>
Date:   Tue Aug 25 13:30:52 2026 +0300

    update template notebook

commit 3b4512564ecdd149e340f78bf7b11a7b34bdc7b9
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> git remote -v                  
origin  https://github.com/ICT-Robotics26/lab1.git (fetch)
origin  https://github.com/ICT-Robotics26/lab1.git (push)
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> 