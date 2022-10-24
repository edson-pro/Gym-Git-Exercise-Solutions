# GIT Exercise

## Bundle 1

### Exercise 1

```bash


D:\projects\git>git init

D:\projects\git>git add .

D:\projects\git>git commit -m "initial commit" 
[main (root-commit) e0edd9a] initial commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

D:\projects\git>git remote add origin https://github.com/edson-pro/git-exercises.git

D:\projects\git>git checkout -b dev
Switched to a new branch 'dev'

D:\projects\git>git push origin dev
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 233 bytes | 116.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/edson-pro/git-exercises/pull/new/dev
remote:
To https://github.com/edson-pro/git-exercises.git
 * [new branch]      dev -> dev

D:\projects\git>git checkout -b test
Switched to a new branch 'test'

D:\projects\git>git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/edson-pro/git-exercises/pull/new/test
remote:
To https://github.com/edson-pro/git-exercises.git
 * [new branch]      test -> test

D:\projects\git>git branch -D test
error: Cannot delete branch 'test' checked out at 'D:/projects/git'

D:\projects\git>git checkout test
Already on 'test'

D:\projects\git>git checkout dev
Switched to branch 'dev'

D:\projects\git>git branch -D test
Deleted branch test (was e0edd9a).

D:\projects\git>git push origin --delete test
To https://github.com/edson-pro/git-exercises.git
 - [deleted]         test

 

```

# Exercices two
```bash
D:\projects\git>git add home.html

D:\projects\git>git stash list

D:\projects\git>git stash
Saved working directory and index state WIP on dev: e0edd9a initial commit

D:\projects\git>git stash list
stash@{0}: WIP on dev: e0edd9a initial commit

D:\projects\git>git stash
No local changes to save

D:\projects\git>git add .

D:\projects\git>git stash 
Saved working directory and index state WIP on dev: e0edd9a initial commit

D:\projects\git>git stash list
stash@{0}: WIP on dev: e0edd9a initial commit
stash@{1}: WIP on dev: e0edd9a initial commit

D:\projects\git>git add .

D:\projects\git>git stash
Saved working directory and index state WIP on dev: e0edd9a initial commit

D:\projects\git>git stash list
stash@{0}: WIP on dev: e0edd9a initial commit
stash@{1}: WIP on dev: e0edd9a initial commit
stash@{2}: WIP on dev: e0edd9a initial commit

D:\projects\git>git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (1e7a8b5fe75c58ed92f6019bf2cd14c18b088149)

D:\projects\git>git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (22a6fc81389d58bc350218b55cf3b09c69565741)

D:\projects\git>git add --all

D:\projects\git>git status
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html


D:\projects\git>git commit -m "set home and about page" 
[dev 50c1bee] set home and about page
 2 files changed, 24 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html

D:\projects\git>git push origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 547 bytes | 136.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/edson-pro/git-exercises.git
   e0edd9a..50c1bee  dev -> dev

D:\projects\git>git stash list
stash@{0}: WIP on dev: e0edd9a initial commit

D:\projects\git>git stash pop stash@{0}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   teams.html

Dropped stash@{0} (049e79bd125f86e8fc1554fb48328f8d499e2184)

D:\projects\git>git reset --hard
HEAD is now at 50c1bee set home and about page

D:\projects\git>git status
On branch dev
nothing to commit, working tree clean
```

# Bundle 2

# Exercices 1
```bash
D:\projects\git>git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

D:\projects\git>git add services.html

D:\projects\git>git commit -m "added services page" 
[ft/bundle-2 e7dec73] added services page
 1 file changed, 12 insertions(+)        
 create mode 100644 services.html        

D:\projects\git>git push origin ft/bundle-2 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 474 bytes | 474.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/edson-pro/git-exercises/pull/new/ft/bundle-2
remote:
To https://github.com/edson-pro/git-exercises.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2

```
 
 # excesises 2
 ```bash
D:\projects\git>
 *  History restored 

Microsoft Windows [Version 10.0.19044.2130]    
(c) Microsoft Corporation. All rights reserved.

D:\projects\git>
 *  History restored 

Microsoft Windows [Version 10.0.19044.2130]    
(c) Microsoft Corporation. All rights reserved.

D:\projects\git>
 *  History restored 

Microsoft Windows [Version 10.0.19044.2130]    
(c) Microsoft Corporation. All rights reserved.

D:\projects\git>git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 630 bytes | 78.00 KiB/s, done.
From https://github.com/edson-pro/git-exercises
   e0edd9a..3a3bfff  main       -> origin/main
Updating e0edd9a..3a3bfff
Fast-forward
 about.html    | 12 ++++++++++++
 home.html     | 12 ++++++++++++
 services.html | 12 ++++++++++++
 3 files changed, 36 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
 create mode 100644 services.html

D:\projects\git>git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

D:\projects\git>git commit -am "added changes to service page" 
[ft/service-redesign 010b191] added changes to service page
 1 file changed, 14 insertions(+), 10 deletions(-)

D:\projects\git>git push origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 381 bytes | 127.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/edson-pro/git-exercises/pull/new/ft/service-redesign
remote:
To https://github.com/edson-pro/git-exercises.git
 * [new branch]      ft/service-redesign -> ft/service-redesign

D:\projects\git>git push origin main
Everything up-to-date

D:\projects\git>git commit -am "added changes to services on main branch" 
[main 64915d2] added changes to services on main branch
 1 file changed, 15 insertions(+), 10 deletions(-)

D:\projects\git>git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 400 bytes | 133.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/edson-pro/git-exercises.git
   3a3bfff..64915d2  main -> main

D:\projects\git>git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

D:\projects\git>git diff

D:\projects\git>git diff

D:\projects\git>git merge main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.

D:\projects\git>git commit -am "merged with main" 
[ft/service-redesign 23e3aad] merged with main

D:\projects\git>git push origin ft/service-redesign
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 363 bytes | 181.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0        
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/edson-pro/git-exercises.git
   010b191..23e3aad  ft/service-redesign -> ft/service-redesign

D:\projects\git>
 ```


 # Bundle 3

 # execises 1

 ```bash

D:\projects\git>git checkout ft/team-page
error: pathspec 'ft/team-page' did not match any file(s) known to git

D:\projects\git>git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'

D:\projects\git>git commit -am "created team page" 
On branch ft/team-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

nothing added to commit but untracked files present (use "git add" to track)

D:\projects\git>git add .

D:\projects\git>git commit -m "created team page" 
[ft/team-page 6c91967] created team page
 1 file changed, 15 insertions(+)       
 create mode 100644 team.html

D:\projects\git>git push origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.    
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 459 bytes | 229.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/edson-pro/git-exercises/pull/new/ft/team-page
remote:
To https://github.com/edson-pro/git-exercises.git
 * [new branch]      ft/team-page -> ft/team-page

D:\projects\git>git checkout -m main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

D:\projects\git>git log
commit 64915d2cc71b85dea22835fd00d7b8e4b3da7941 (HEAD -> main, origin/main)
Author: ntwali edson <ntwaliedson9@gmail.com>
Date:   Fri Oct 21 12:13:41 2022 +0200

    added changes to services on main branch

commit 3a3bfffd99d5fc02fd829a06789bd7a01ae0fe33
Merge: e0edd9a e7dec73
Author: Chrissie <chrissiemhrk@gmail.com>
Date:   Wed Oct 19 20:32:36 2022 +0200

    Merge pull request #1 from edson-pro/ft/bundle-2

    Add new pages to the project

D:\projects\git>ft/contact-page
'ft' is not recognized as an internal or external command,
operable program or batch file.

D:\projects\git>git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

D:\projects\git>git cherry-pick   
usage: git cherry-pick [<options>] <commit-ish>...
   or: git cherry-pick <subcommand>

    --quit                end revert or cherry-pick sequence
    --continue            resume revert or cherry-pick sequence
    --abort               cancel revert or cherry-pick sequence
    --skip                skip current commit and continue
    --cleanup <mode>      how to strip spaces and #comments from message
    -n, --no-commit       don't automatically commit
    -e, --edit            edit the commit message
    -s, --signoff         add a Signed-off-by trailer
    -m, --mainline <parent-number>
                          select mainline parent
    --rerere-autoupdate   update the index with reused conflict resolution if p
    --strategy <strategy>
                          merge strategy
    -X, --strategy-option <option>
                          option for merge strategy
    -S, --gpg-sign[=<key-id>]
                          GPG sign commit
    -x                    append commit name
    --ff                  allow fast-forward
    --allow-empty         preserve initially empty commits
    --allow-empty-message
                          allow commits with empty messages
    --keep-redundant-commits
                          keep redundant, empty commits


D:\projects\git>git commit -am "added contact page" 
On branch ft/contact-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        contact.html

nothing added to commit but untracked files present (use "git add" to track)

D:\projects\git>git add .

D:\projects\git>git commit -am "added contact page" 
[ft/contact-page cd333ae] added contact page
 1 file changed, 15 insertions(+)
 create mode 100644 contact.html

D:\projects\git>git push origin ft/contact-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 457 bytes | 228.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/edson-pro/git-exercises/pull/new/ft/contact-pag
remote:
To https://github.com/edson-pro/git-exercises.git
 * [new branch]      ft/contact-page -> ft/contact-page

D:\projects\git>git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

D:\projects\git>faq.html
'faq.html' is not recognized as an internal or external command,
operable program or batch file.

D:\projects\git>git add .

D:\projects\git>git commit -m "added faq page" 
[ft/faq-page cfbd95e] added faq page
 1 file changed, 15 insertions(+)
 create mode 100644 faq.html

D:\projects\git>git push origin ft/faq-page
Enumerating objects: 4, done.
Revert "added changes to services on main branch"
Revert "added changes to services on main branch"
Revert "added changes to services on main branch"

remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/edson-pro/git-exercises/pull/new/ft/faq-page   
remote:
To https://github.com/edson-pro/git-exercises.git
 * [new branch]      ft/faq-page -> ft/faq-page

D:\projects\git>git revert 64915d2cc71b85dea22835fd00d7b8e4b3da7941
[ft/faq-page 398f570] Revert "added changes to services on main branch"
 1 file changed, 10 insertions(+), 15 deletions(-)

D:\projects\git>git add .

D:\projects\git>git commit -m "created faq page" 
On branch ft/faq-page
nothing to commit, working tree clean

D:\projects\git>git push origin ft/faq-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 424 bytes | 212.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0        
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/edson-pro/git-exercises.git
   cfbd95e..398f570  ft/faq-page -> ft/faq-page

D:\projects\git>
 ```



# exercises 2

```bash

D:\projects\git>git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'

D:\projects\git>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

D:\projects\git>git checkout ft/home-page-redesign   
Switched to branch 'ft/home-page-redesign'
M       home.html

D:\projects\git> 
 *  History restored 

Microsoft Windows [Version 10.0.19044.2130]
(c) Microsoft Corporation. All rights reserved.

D:\projects\git>git commit -m "added some change" 
On branch ft/home-page-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

Untracked files:
  (use "git add <file>..." to include in what will be committed) 
        changes

no changes added to commit (use "git add" and/or "git commit -a")

D:\projects\git>git add .

D:\projects\git>git commit -m "added some changes" 
[ft/home-page-redesign b9ae783] added some changes
 2 files changed, 15 insertions(+), 10 deletions(-)
 create mode 100644 changes

D:\projects\git>git push origin ft/home-page-redesign
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 419 bytes | 69.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.        
remote: 
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/edson-pro/git-exercises/pull/new/ft/home-page-redesign
remote:
To https://github.com/edson-pro/git-exercises.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign

D:\projects\git>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

D:\projects\git>git commit -m "added changes" 
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)      
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")

D:\projects\git>git add /
fatal: /: '/' is outside repository at 'D:/projects/git'

D:\projects\git>git add .

D:\projects\git>git commit -m "added some new changes" 
[main d9bd0f2] added some new changes
 1 file changed, 18 insertions(+), 9 deletions(-)

D:\projects\git>git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 401 bytes | 100.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.        
To https://github.com/edson-pro/git-exercises.git
   64915d2..d9bd0f2  main -> main

D:\projects\git>git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

D:\projects\git>git rebase main
Auto-merging home.html
CONFLICT (content): Merge conflict in home.html
error: could not apply b9ae783... added some changes
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".     
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply b9ae783... added some changes

D:\projects\git>git add .

D:\projects\git>git commit -m "made rebase with main" 
[detached HEAD a7e5651] made rebase with main
 2 files changed, 2 insertions(+), 1 deletion(-)
 create mode 100644 changes

D:\projects\git>git git push origin ft/home-page-redesign
git: 'git' is not a git command. See 'git --help'.

The most similar command is
        init

D:\projects\git>git push origin ft/home-page-redesign
Everything up-to-date

D:\projects\git>git commit -m "made rebase" 
On branch ft/home-page-redesign
Last commands done (4 commands done):
   pick 398f570 Revert "added changes to services on main branch"
   pick b9ae783 added some changes
  (see more in file .git/rebase-merge/done)
No commands remaining.
You are currently editing a commit while rebasing branch 'ft/home-page-redesign' on 'd9bd0f2'.
  (use "git commit --amend" to amend the current commit)
  (use "git rebase --continue" once you are satisfied with your changes)

nothing to commit, working tree clean

D:\projects\git>git log
commit b9ae783092eacca8e490fea86a2c12e5cfef8a2c (HEAD -> ft/home-page-redesign, origin/ft/home-page-redesign)
Author: ntwali edson <ntwaliedson9@gmail.com>
Date:   Mon Oct 24 07:17:49 2022 +0200

    added some changes

commit 398f57058c9a5ecbbecd15398fac55ae96654b60 (origin/ft/faq-page, ft/faq-page)
Author: ntwali edson <ntwaliedson9@gmail.com>
Date:   Fri Oct 21 16:13:45 2022 +0200

    Revert "added changes to services on main branch"

    This reverts commit 64915d2cc71b85dea22835fd00d7b8e4b3da7941.

commit cfbd95e822f2968c443f64cc5c239b3255360d6b
Author: ntwali edson <ntwaliedson9@gmail.com>
Date:   Fri Oct 21 14:40:52 2022 +0200


D:\projects\git>
D:\projects\git>git add home.html

D:\projects\git>git commit -m "added changes" 
[ft/home-page-redesign 6c95594] added changes
 1 file changed, 2 insertions(+)

D:\projects\git>git push origin ft/home-page-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 328 bytes | 109.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/edson-pro/git-exercises.git
   b9ae783..6c95594  ft/home-page-redesign -> ft/home-page-redesign

D:\projects\git>

```


# bunde 4

# execrcies 1

```bash 

D:\projects\git>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

D:\projects\git>git add home.html

D:\projects\git>git commit -m "added changes to the home" 
[main 9b7bfc7] added changes to the home
 1 file changed, 2 insertions(+)        

D:\projects\git>git remote add origin https://github.com/edson-pro/git-copy.git
error: remote origin already exists.

D:\projects\git>git remote add git-copy https://github.com/edson-pro/git-copy.git 

D:\projects\git>git remote
git-copy
origin

D:\projects\git>git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 335 bytes | 167.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/edson-pro/git-exercises.git
   d9bd0f2..9b7bfc7  main -> main

D:\projects\git>git push git-copy main
Enumerating objects: 20, done.
Counting objects: 100% (20/20), done.
Delta compression using up to 4 threads
Compressing objects: 100% (18/18), done.
Writing objects: 100% (20/20), 2.54 KiB | 96.00 KiB/s, done.
Total 20 (delta 8), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (8/8), done.
To https://github.com/edson-pro/git-copy.git
 * [new branch]      main -> main

D:\projects\git>

```

# Exercise 2

```bash 

D:\projects\git>git checkout -b ft/footer
Switched to a new branch 'ft/footer'

D:\projects\git>git commit -am "added footer" 
On branch ft/footer
Last commands done (4 commands done):
   pick 398f570 Revert "added changes to services on main branch"
   pick b9ae783 added some changes
  (see more in file .git/rebase-merge/done)
No commands remaining.
You are currently editing a commit while rebasing branch 'ft/home-page-redesign' on 'd9bd0f2'.
  (use "git commit --amend" to amend the current commit)
  (use "git rebase --continue" once you are satisfied with your changes)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        footer.html

nothing added to commit but untracked files present (use "git add" to track)

D:\projects\git>git add .

D:\projects\git>git commit -m "added footer" 
[ft/footer 8755075] added footer
 1 file changed, 15 insertions(+)
 create mode 100644 footer.html

D:\projects\git>git push origin ft/footergit commit -m "added footer"

D:\projects\git>git commit -m "added other changes to the footer" 
On branch ft/footer
Last commands done (4 commands done):
   pick 398f570 Revert "added changes to services on main branch"
   pick b9ae783 added some changes
  (see more in file .git/rebase-merge/done)
No commands remaining.
You are currently editing a commit while rebasing branch 'ft/home-page-redesign' on 'd9bd0f2'.
  (use "git commit --amend" to amend the current commit)
  (use "git rebase --continue" once you are satisfied with your changes)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   footer.html

no changes added to commit (use "git add" and/or "git commit -a")

D:\projects\git>git add .

D:\projects\git>git commit -m "added other changes to the footer" 
[ft/footer 026ef5e] added other changes to the footer
 1 file changed, 3 insertions(+)

D:\projects\git>git push origin ft/footer
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 751 bytes | 125.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/edson-pro/git-exercises/pull/new/ft/footer
remote:
To https://github.com/edson-pro/git-exercises.git
 * [new branch]      ft/footer -> ft/footer

D:\projects\git>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

D:\projects\git>git checkout -b ft/squashing 
Switched to a new branch 'ft/squashing'

D:\projects\git>git merge --squash ft/footer 
Updating 9b7bfc7..026ef5e
Fast-forward
Squash commit -- not updating HEAD
 footer.html | 18 ++++++++++++++++++
 1 file changed, 18 insertions(+)
 create mode 100644 footer.html

D:\projects\git>git add .      

D:\projects\git>git commit -m "footer changes squashing" 
[ft/squashing 3242c84] footer changes squashing
 1 file changed, 18 insertions(+)
 create mode 100644 footer.html

D:\projects\git>git push origin ft/squashing
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 484 bytes | 161.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/edson-pro/git-exercises/pull/new/ft/squashing
remote:
To https://github.com/edson-pro/git-exercises.git
 * [new branch]      ft/squashing -> ft/squashing


```


# bunde 5

# exrcises 2

```bash

Microsoft Windows [Version 10.0.19044.2130]
(c) Microsoft Corporation. All rights reserved.

D:\projects\git-cafe-exercise>git add index.html

D:\projects\git-cafe-exercise>git commit -m "changed the main title" 
[main 7c4532d] changed the main title
 1 file changed, 283 insertions(+), 226 deletions(-)

D:\projects\git-cafe-exercise>  git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.38 KiB | 472.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0       
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/edson-pro/git-cafe-exercise.git
   d1d3f9c..7c4532d  main -> main

D:\projects\git-cafe-exercise>
```