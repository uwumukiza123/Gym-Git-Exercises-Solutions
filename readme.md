# git exercises

this project is all about commands needed to start with git and master it

## bundle 1

### exercise 1

```bash

nothing to commit (create/copy files and use "git add" to track)                                                        
PS C:\Users\ABC\Desktop\THE GYM\git-exercises> git branch   
PS C:\Users\ABC\Desktop\THE GYM\git-exercises> git branch -M main main
PS C:\Users\ABC\Desktop\THE GYM\git-exercises> git branch   
PS C:\Users\ABC\Desktop\THE GYM\git-exercises> git status   
On branch main

nothing to commit (create/copy files and use "git add" to track)                                                        ack)
PS C:\Users\ABC\Desktop\THE GYM\git-exercises> git status   
On branch main

No commits yet

Untracked files:
ted)
Changes to be committed:
        new file:   readme.md

PS C:\Users\ABC\Desktop\THE GYM\git-exercises> git commit -m 'first commit in gym-gi
[main (root-commit) 75b7c27] first commit in gym-git-exercise
 1 file changed, 0 insertions(+), 0 deletions(-)
PS C:\Users\ABC\Desktop\THE GYM\git-exercises>


                                               git remote add origin https://github.
PS C:\Users\ABC\Desktop\THE GYM\git-exercises>


To push the current branch and set the remote as upstream, u
    git push --set-upstream origin main

PS C:\Users\ABC\Desktop\THE GYM\git-exercises> git push --set-upstream origin main  
Enumerating objects: 3, done.
Writing objects: 100% (3/3), 242 bytes | 60.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\ABC\Desktop\THE GYM\git-exercises> git checkout -b dev
                                    Switched to a new branch 'dev'
PS C:\Users\ABC\Desktop\THE GYM\git-exercises> git status
nothing to commit, working tree clean
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

PS C:\Users\ABC\Desktop\THE GYM\git-exercises> git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote:      https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions/pull/new/deremote:
 * [new branch]      dev -> dev
Switched to a new branch 'test'
PS C:\Users\ABC\Desktop\THE GYM\git-exercises> git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions/pull/new/test
remote:
To https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions.git
 * [new branch]      test -> test
PS C:\Users\ABC\Desktop\THE GYM\git-exercises> git checkout dev
Switched to branch 'dev'
PS C:\Users\ABC\Desktop\THE GYM\git-exercises> git checkout -d test
HEAD is now at 75b7c27 first commit in gym-git-exercise
PS C:\Users\ABC\Desktop\THE GYM\git-exercises> git push origin dev
Everything up-to-date
PS C:\Users\ABC\Desktop\THE GYM\git-exercises> git push origin --delete test        
To https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions.git
 - [deleted]         test
PS C:\Users\ABC\Desktop\THE GYM\git-exercises>

```