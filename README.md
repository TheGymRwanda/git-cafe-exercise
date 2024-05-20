# git-cafe-exercise


```bash

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native
$ git clone https://github.com/IGIRANEZAJosue/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 93
Receiving objects: 100% (107/107), 1.95 MiB | 799.00 KiB/s, done.
Resolving deltas: 100% (5/5), done.

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native
$ cd git-cafe-exercise

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (main)
$ code .

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (main)
$ git add .

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html


Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (main)
$ git commit -m "Change text to 'Welcome to our restaurant'"
[main 08f51ce] Change text to 'Welcome to our restaurant'
 1 file changed, 16 insertions(+), 16 deletions(-)

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 556 bytes | 556.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/IGIRANEZAJosue/git-cafe-exercise.git
   d1d3f9c..08f51ce  main -> main

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (main)
$


```

# Bundle 6

```bash

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (main)
$ git checkout -b feature/add-menu-page
Switched to a new branch 'feature/add-menu-page'

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (feature/add-menu-page)
$ git add menu.html

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (feature/add-menu-page)
$ git status
On branch feature/add-menu-page
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   menu.html


Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (feature/add-menu-page)
$ git commit -m "Add menu page"
[feature/add-menu-page 3e39759] Add menu page
 1 file changed, 11 insertions(+)
 create mode 100644 menu.html

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (feature/add-menu-page)
$ git push origin feature/add-menu-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 427 bytes | 427.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'feature/add-menu-page' on GitHub by visiting:
remote:      https://github.com/IGIRANEZAJosue/git-cafe-exercise/pull/new/feature/add-menu-page
remote:
To https://github.com/IGIRANEZAJosue/git-cafe-exercise.git
 * [new branch]      feature/add-menu-page -> feature/add-menu-page

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (feature/add-menu-page)
$ git checkout -b bugfix/change-title
Switched to a new branch 'bugfix/change-title'

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (bugfix/change-title)
$ git add index-4.html

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (bugfix/change-title)
$ git status
On branch bugfix/change-title
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index-4.html


Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (bugfix/change-title)
$ git commit -m "Change title to 'Contact'"
[bugfix/change-title 932d223] Change title to 'Contact'
 1 file changed, 4 insertions(+), 4 deletions(-)

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (bugfix/change-title)
$ git push origin bugfix/change-title
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 389 bytes | 389.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'bugfix/change-title' on GitHub by visiting:
remote:      https://github.com/IGIRANEZAJosue/git-cafe-exercise/pull/new/bugfix/change-title
remote:
To https://github.com/IGIRANEZAJosue/git-cafe-exercise.git
 * [new branch]      bugfix/change-title -> bugfix/change-title

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (bugfix/change-title)
$ ^[[200~git checkout -b hotfix/change-telephone
bash: $'\E[200~git': command not found

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (bugfix/change-title)
$ git checkout -b hotfix/change-telephone
Switched to a new branch 'hotfix/change-telephone'

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (hotfix/change-telephone)
$ git add index-4.html

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (hotfix/change-telephone)
$ git status
On branch hotfix/change-telephone
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index-4.html


Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (hotfix/change-telephone)
$ git commit -m "Change telephone number"
[hotfix/change-telephone 02b8707] Change telephone number
 1 file changed, 1 insertion(+), 1 deletion(-)

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (hotfix/change-telephone)
$ git push origin hotfix/change-telephone
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 306 bytes | 153.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'hotfix/change-telephone' on GitHub by visiting:
remote:      https://github.com/IGIRANEZAJosue/git-cafe-exercise/pull/new/hotfix/change-telephone
remote:
To https://github.com/IGIRANEZAJosue/git-cafe-exercise.git
 * [new branch]      hotfix/change-telephone -> hotfix/change-telephone

Igiraneza@DESKTOP-2M35984 MINGW64 ~/desktop/Native/git-cafe-exercise (hotfix/change-telephone)
$


```