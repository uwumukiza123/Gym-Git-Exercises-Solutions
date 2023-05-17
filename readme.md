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

## Bundle 3

### Exercise 1

```bash

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/service-redesign)
$ git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/team-page)
$ touch team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/team-page)
$ git add team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/team-page)
$ git commit -m 'add team page to our html file'
[ft/team-page edd31b3] add team page to our html file
 1 file changed, 12 insertions(+)
 create mode 100644 team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/team-page)
$ git push
fatal: The current branch ft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/team-page


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/team-page)
$ git push --set-upstream origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 497 bytes | 124.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions/pull/new/ft/team-page
remote:
To https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/team-page)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git checkout ft/contact-page
error: pathspec 'ft/contact-page' did not match any file(s) known to git

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (main)
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/team-page)
$ git log
commit edd31b3bbfe5c0faa1b3a568b5b9e62d8b2e1fcc (HEAD -> ft/team-page, origin/ftcommit edd31b3bbfe5c0faa1b3a568b5b9e62d8b2e1fcc (HEAD -> ft/team-page, origin/ft
/team-page)
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Wed May 17 12:49:40 2023 +0200

    add team page to our html file

commit 31dccd1fe050c6430d75d3dde8905dfe3bf93871 (origin/ft/service-redesign, ft/service-redesign)
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Tue May 16 18:01:07 2023 +0200

    add readme.md

commit 4bc47f015311bf000eb2a2517493a220bddd4241
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Tue May 16 13:59:03 2023 +0200

    add exercise2 on readme.md

commit 5cf78c3497c12e2a24cacc02c6cb8f250f073155
Merge: aa580d2 f3f17b7
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Tue May 16 13:42:53 2023 +0200

    Merge branch 'main' into ft/service-redesign

commit f3f17b713cd913967fb09f3eeb6a8567402fd77f (origin/main, origin/HEAD, main, ft/contact-page)
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Tue May 16 11:55:19 2023 +0200

    adding changes in services page

commit aa580d2985a71f8b920dfc7626941323222a173e
Author: Laetitia UWUMUKIZA <uwumukizalaetitia@gmail.com>
Date:   Tue May 16 11:33:48 2023 +0200

    adding some changes to services.html

commit 69c5319962398dab944cba3f89a87a1c5f9d0742
Merge: 75b7c27 85b1cfb
Author: uwumukiza123 <113632531+uwumukiza123@users.noreply.github.com>
Date:   Tue May 16 11:06:49 2023 +0200

    Merge pull request #1 from uwumukiza123/ft/bundle-2

    adding different pages to this project

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/team-page)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/team-page)
$  git checkout ft/contact-page
Switched to branch 'ft/contact-page'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/contact-page)
$ git cherry-pick edd31b3bbfe5c0faa1b3a568b5b9e62d8b2e1fcc
[ft/contact-page 969b9c0] add team page to our html file
 Date: Wed May 17 12:49:40 2023 +0200
 1 file changed, 12 insertions(+)
 create mode 100644 team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/contact-page)
$ git add contact.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/contact-page)
$ git commit -m 'add new page to out html file'
[ft/contact-page 672bc81] add new page to out html file
 1 file changed, 12 insertions(+)
 create mode 100644 contact.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/contact-page)
$ git push
fatal: The current branch ft/contact-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/contact-page


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/contact-page)
$ git push --set-upstream origin ft/contact-page
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 780 bytes | 260.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions/pull/new/ft/contact-page
remote:
To https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/contact-page)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/faq-page)
$ ls
about.html  contact.html  fag.html  home.html  readme.md  services.html  team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/faq-page)
$ git add faq.html
fatal: pathspec 'faq.html' did not match any files

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/faq-page)
$ ls
about.html  contact.html  faq.html  home.html  readme.md  services.html  team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/faq-page)
$ cd faq.html
bash: cd: faq.html: Not a directory

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/faq-page)
$ git add faq.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/faq-page)
$ git commit -m 'add faq.html'
[ft/faq-page 3217735] add faq.html
 1 file changed, 12 insertions(+)
 create mode 100644 faq.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/faq-page)
$ git push origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 466 bytes | 466.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions/pull/new/ft/faq-page
remote:
To https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions.git
 * [new branch]      ft/faq-page -> ft/faq-page

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/faq-page)
$

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/faq-page)
$ git revert edd31b3bbfe5c0faa1b3a568b5b9e62d8b2e1fcc
[ft/faq-page 2e463c5] Revert "add team page to our html file"
 1 file changed, 12 deletions(-)
 delete mode 100644 team.html

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/faq-page)
$ git add .

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/faq-page)
$ git push
fatal: The current branch ft/faq-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/faq-page


ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/faq-page)
$ git push --set-upstream origin ft/faq-page
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 298 bytes | 298.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/uwumukiza123/Gym-Git-Exercises-Solutions.git
   3217735..2e463c5  ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.

ABC@DESKTOP-8KGAEGA MINGW64 ~/Desktop/THE GYM/Gym-Git-Exercises-Solutions (ft/faq-page)
$
```