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
 