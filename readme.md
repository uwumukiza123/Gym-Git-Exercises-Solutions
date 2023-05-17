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

### exercise 2

```bash
ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ ls
home.html  readme.md

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git status
On branch dev
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        home.html

nothing added to commit but untracked files present (use "git add" to track)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git stash list

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git add home.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git status
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   home.html


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 2a2352e first exercise in bundle 1

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git stash list
stash@{0}: WIP on dev: 2a2352e first exercise in bundle 1

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ touch about.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git add about.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 2a2352e first exercise in bundle 1

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git stash list
stash@{0}: WIP on dev: 2a2352e first exercise in bundle 1
stash@{1}: WIP on dev: 2a2352e first exercise in bundle 1

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ touch team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git status
On branch dev
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

nothing added to commit but untracked files present (use "git add" to track)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git add team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 2a2352e first exercise in bundle 1

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git stash list
stash@{0}: WIP on dev: 2a2352e first exercise in bundle 1
stash@{1}: WIP on dev: 2a2352e first exercise in bundle 1
stash@{2}: WIP on dev: 2a2352e first exercise in bundle 1

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (eca0035b01087f79ae66924d749915261e7022b8)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git stash list
stash@{0}: WIP on dev: 2a2352e first exercise in bundle 1
stash@{1}: WIP on dev: 2a2352e first exercise in bundle 1

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (080ce35ed667515d17e26a40ed3d9fe00134ea23)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git add --all

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git commit -m 'restore home and about page'
[dev 411da8d] restore home and about page
 2 files changed, 26 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git push --set-upstream origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 597 bytes | 298.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions.git
   2a2352e..411da8d  dev -> dev
branch 'dev' set up to track 'origin/dev'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git stash list
stash@{0}: WIP on dev: 2a2352e first exercise in bundle 1

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git stash stash@{0}
fatal: unknown subcommand: stash@{0}

usage: git stash list [<options>]
   or: git stash show [<options>] [<stash>]
   or: git stash drop [-q|--quiet] [<stash>]
   or: git stash ( pop | apply ) [--index] [-q|--quiet] [<stash>]
   or: git stash branch <branchname> [<stash>]
   or: git stash clear
   or: git stash [push [-p|--patch] [-S|--staged] [-k|--[no-]keep-index] [-q|--quiet]
                 [-u|--include-untracked] [-a|--all] [-m|--message <message>]
                 [--pathspec-from-file=<file> [--pathspec-file-nul]]
                 [--] [<pathspec>...]]
   or: git stash save [-p|--patch] [-S|--staged] [-k|--[no-]keep-index] [-q|--quiet]
                 [-u|--include-untracked] [-a|--all] [<message>]


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git stash pop stash@{0}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped stash@{0} (9986c6258f11d141b61ea1117aa7ccfd8174fafd)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git reset --hard
HEAD is now at 411da8d restore home and about page

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$
```
## Bundle 2

### exercise 1

```bash

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (dev)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (ft/bundle-2)
$ touch service.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (ft/bundle-2)
$ ls
about.html  home.html  readme.md  services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (ft/bundle-2)
$ git status
On branch ft/bundle-2
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        services.html

no changes added to commit (use "git add" and/or "git commit -a")

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (ft/bundle-2)
$ git add services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (ft/bundle-2)
$ git stash
Saved working directory and index state WIP on bundle-2: 4014905 adding exercise 2 on readme.md

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (ft/bundle-2)
$ git stash pop
On branch ft/bundle-2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   services.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md

Dropped refs/stash@{0} (fc2d64e3a0fcefa8bd42e740d8beb4e73c6b019e)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (ft/bundle-2)
$ git add services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (ft/bundle-2)
$ git commit -m 'creating and adding some changes in service page'
[ft/bundle-2 6bb7f18] creating and adding some changes in service page
 1 file changed, 12 insertions(+)
 create mode 100644 services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (ft/bundle-2)
$ git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (ft/bundle-2)
$ git push --set-upstream origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 524 bytes | 524.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions/pull/new/ft/bundle-2
remote:
To https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-exercises (ft/bundle-2)
$
```

### exercise 2

```bash


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git pull
Already up to date.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 646 bytes | 15.00 KiB/s, done.
From https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions
   75b7c27..69c5319  main       -> origin/main
Updating 75b7c27..69c5319
Fast-forward
 about.html    |  12 ++
 home.html     |  14 +++
 readme.md     | 354 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 services.html |  12 ++
 4 files changed, 392 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
 create mode 100644 services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$ ls
readme.md

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$ ls
readme.md

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$ git status
On branch ft/service-redesign
nothing to commit, working tree clean

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ ls
about.html  home.html  readme.md  services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git branch -D ft/service-redesign
Deleted branch ft/service-redesign (was 75b7c27).

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git chechout -b ft/service-redesign
git: 'chechout' is not a git command. See 'git --help'.

The most similar command is
        checkout

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$ ls
about.html  home.html  readme.md  services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$ git add services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$ git commit -m 'adding some changes to services.html'
[ft/service-redesign aa580d2] adding some changes to services.html
 1 file changed, 2 insertions(+)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$ git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 386 bytes | 193.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions/pull/new/ft/service-redesign
remote:
To https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$ ^C

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git add services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git commit -m 'adding changes in services page'
[main f3f17b7] adding changes in services page
 1 file changed, 2 insertions(+)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 380 bytes | 380.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions.git
   69c5319..f3f17b7  main -> main

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$ git merge main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign|MERGING)
$ git add services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign|MERGING)
$ git commit
[ft/service-redesign 5cf78c3] Merge branch 'main' into ft/service-redesign

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$ git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
```

