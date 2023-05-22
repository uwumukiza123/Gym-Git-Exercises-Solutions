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

## Bundle 4

## Exercise 1

```Bash

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/home-page-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git remote add git-copy https://github.com/uwumukiza123/gym-git-exercises-second-part.git

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git remote
git-copy
origin

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git add home.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git commit -m 'add home page'
[main a68d96d] add home page
 1 file changed, 2 insertions(+)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 329 bytes | 329.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions.git
   b0901a7..a68d96d  main -> main

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git push git-copy
Enumerating objects: 29, done.
Counting objects: 100% (29/29), done.
Delta compression using up to 4 threads
Compressing objects: 100% (19/19), done.
Writing objects: 100% (29/29), 5.94 KiB | 1.49 MiB/s, done.
Total 29 (delta 13), reused 18 (delta 7), pack-reused 0
remote: Resolving deltas: 100% (13/13), done.
To https://github.com/uwumukiza123/gym-git-exercises-second-part.git
 * [new branch]      main -> main

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$
```

## Bundle 5

### exercise 1

```Bash

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/squashing)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git pull
Already up to date.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git add index.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    home.html


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git add home.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git commit -m 'rename home.html to index.html'
[main 373b3f6] rename home.html to index.html
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename home.html => index.html (100%)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 261 bytes | 261.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions.git
   30582d0..373b3f6  main -> main

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$
```

### exercise 2

```Bash
ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ cd ..

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM
$ git clone https://github.com/uwumukiza123/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 100
Receiving objects: 100% (107/107), 1.95 MiB | 562.00 KiB/s, done.
Resolving deltas: 100% (5/5), done.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM
$ ls
 Gym-Git-Exercises-Solutions/  'THE GYM FIRST WEBSITE'/  'THE GYM PRACTICE'/   git-cafe-exercise/

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM
$ cd git-cafe-exercise/

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (main)
$ code .

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (main)
$ git add index.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (main)
$ git commit -m 'edit home page and add some changes in there'
[main 2cc0b80] edit home page and add some changes in there
 1 file changed, 1 insertion(+), 1 deletion(-)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 355 bytes | 177.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/uwumukiza123/git-cafe-exercise.git
   d1d3f9c..2cc0b80  main -> main

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (main)
$
```

## Bundle 6

### exercise 1

```Bash
ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ ls
about.html  index.html  readme.md  services.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ cd ..

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM
$ ls
 Gym-Git-Exercises-Solutions/  'THE GYM FIRST WEBSITE'/  'THE GYM PRACTICE'/   git-cafe-exercise/

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM
$ cd git-cafe-exercise/

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (main)
$ ls
README.md  bat/  css/  images/  index-1.html  index-2.html  index-3.html  index-4.html  index.html  js/

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (main)
$ git checkout -b ft-branch
Switched to a new branch 'ft-branch'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (ft-branch)
$ ls
README.md  css/     index-1.html  index-3.html  index.html
bat/       images/  index-2.html  index-4.html  js/

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (ft-branch)
$ code .

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (ft-branch)
$ ls
README.md  bat/  css/  images/  index-1.html  index-2.html  index-3.html  index-4.html  index.html  js/

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (ft-branch)
$ git add .

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (ft-branch)
$ git commit -m 'add menu page to our JS folder'
[ft-branch e97a713] add menu page to our JS folder
 2 files changed, 27 insertions(+)
 create mode 100644 .vscode/settings.json
 create mode 100644 js/Menu.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (ft-branch)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (ft-branch)
$ git status
On branch ft-branch
nothing to commit, working tree clean

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (ft-branch)
$ git push origin ft-branch
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 755 bytes | 31.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft-branch' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/git-cafe-exercise/pull/new/ft-branch
remote:
To https://github.com/uwumukiza123/git-cafe-exercise.git
 * [new branch]      ft-branch -> ft-branch

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (ft-branch)
$
```

### Exercise 2

```Bash

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (ft-branch)
$ git checkout -b bug-fix-branch
Switched to a new branch 'bug-fix-branch'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (bug-fix-branch)
$ git add Contact.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (bug-fix-branch)
$ git commit -m 'rename index-4.html file to contact.html'
[bug-fix-branch 42c9b38] rename index-4.html file to contact.html
 1 file changed, 204 insertions(+)
 create mode 100644 Contact.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (bug-fix-branch)
$ git push
fatal: The current branch bug-fix-branch has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin bug-fix-branch


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (bug-fix-branch)
$ git push --set-upstream origin bug-fix-branch
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 2.51 KiB | 428.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'bug-fix-branch' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/git-cafe-exercise/pull/new/bug-fix-branch
remote:
To https://github.com/uwumukiza123/git-cafe-exercise.git
 * [new branch]      bug-fix-branch -> bug-fix-branch
branch 'bug-fix-branch' set up to track 'origin/bug-fix-branch'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (bug-fix-branch)
```

### exercise 3

```Bash


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise/js (bug-fix-branch)
$ git checkout -b contact-branch
Switched to a new branch 'contact-branch'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise/js (contact-branch)
$ ls
Menu.html      html5shiv.js             jquery.equalheights.js      jquery.js                        jquery.rd-google-map.js            jquery.unveil.js  tmstickup.js
TMForm.js      jquery-migrate-1.2.1.js  jquery.fancybox-buttons.js  jquery.mobile.customized.min.js  jquery.rd-parallax.js              modal.js          wow.js
camera.js      jquery.cookie.js         jquery.fancybox-media.js    jquery.mobilemenu.js             jquery.simplr.smoothscroll.min.js  script.js
device.min.js  jquery.easing.1.3.js     jquery.fancybox.js          jquery.mousewheel.min.js         jquery.ui.totop.js                 superfish.js

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise/js (contact-branch)
$ cd ..

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (contact-branch)
$ ls
Contact.html  README.md  bat/  css/  images/  index-1.html  index-2.html  index-3.html  index.html  js/

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (contact-branch)
$ git add Contact.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (contact-branch)
$ git commit 'add contact changes to contact.html page'
error: pathspec 'add contact changes to contact.html page' did not match any file(s) known to git

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (contact-branch)
$ git commit -m 'add changes to contact.html page'
[contact-branch edcaeac] add changes to contact.html page
 1 file changed, 1 insertion(+), 1 deletion(-)

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/git-cafe-exercise (contact-branch)
$ git push origin contact-branch
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 325 bytes | 108.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'contact-branch' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/git-cafe-exercise/pull/new/contact-branch
remote:
To https://github.com/uwumukiza123/git-cafe-exercise.git
 * [new branch]      contact-branch -> contact-branch

ABC@
```