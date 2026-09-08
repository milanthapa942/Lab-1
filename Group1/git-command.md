 C:\Users\admin\OneDrive\Documents\GitHub\lab1> git branch -a
* main
 
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
