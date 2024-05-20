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