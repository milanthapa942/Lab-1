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
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> git status
On branch group-06
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        99/group-06/

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> git add group-06/git-command.md
fatal: pathspec 'group-06/git-command.md' did not match any files
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> 
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1> cd 99  
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1\99> git branch -a                  
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
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1\99> git branch group-06            
fatal: a branch named 'group-06' already exists
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1\99> git checkout group-06          
Already on 'group-06'
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1\99> git log                        
commit b02a1a98a2cd4c4f7f8d81058a3f5e505e076192 (HEAD -> group-06, origin/DevSanz)
Author: naplyon3 <naplyon3@hotmail.com>
Date:   Thu Sep 3 14:16:18 2026 +0300

    Create ReadMe.md

commit 511e5bdfa096d333977468cb63f520f0108a4592
Author: Leo Li <leo.li@hamk.fi>
Date:   Tue Aug 25 13:30:52 2026 +0300

    update template notebook

commit 3b4512564ecdd149e340f78bf7b11a7b34bdc7b9
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1\99> git remote -v                  
origin  https://github.com/ICT-Robotics26/lab1.git (fetch)
origin  https://github.com/ICT-Robotics26/lab1.git (push)
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1\99> git status                     
On branch group-06
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        group-06/

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1\99> git add group-06/git-command.md
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1\99> git commit -m "Add Git command result for group 06"
[group-06 dcad046] Add Git command result for group 06
 1 file changed, 36 insertions(+)
 create mode 100644 99/group-06/git-command.md
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1\99> git push -u origin group-06
info: please complete authentication in your browser...
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 979 bytes | 489.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'group-06' on GitHub by visiting:
remote:      https://github.com/ICT-Robotics26/lab1/pull/new/group-06
remote: 
To https://github.com/ICT-Robotics26/lab1.git
 * [new branch]      group-06 -> group-06
branch 'group-06' set up to track 'origin/group-06'.
PS C:\Users\USER\OneDrive - Hämeen ammattikorkeakoulu\lab1\99> 