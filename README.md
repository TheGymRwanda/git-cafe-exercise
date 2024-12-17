# git-cafe-exercise
## Bundle 5 
### Exercise 2

```bash
HOSA.LTD@DESKTOP-JOJFIGL MINGW64 ~ (master)
$ git clone https://github.com/berniceu/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 93 (from 1)
Receiving objects: 100% (107/107), 1.95 MiB | 2.85 MiB/s, done.
Resolving deltas: 100% (5/5), done.

HOSA.LTD@DESKTOP-JOJFIGL MINGW64 ~ (master)
$ code .

HOSA.LTD@DESKTOP-JOJFIGL MINGW64 ~ (master)
$ cd git-cafe-exercise/
HOSA.LTD@DESKTOP-JOJFIGL MINGW64 ~ (master)
$  git add .
HOSA.LTD@DESKTOP-JOJFIGL MINGW64 ~ (master)
$ git commit -m "change heading"
[main 92404ec] change heading
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\HOSA.LTD\git-cafe-exercise> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 317 bytes | 317.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.  
To https://github.com/berniceu/git-cafe-exercise.git
   d1d3f9c..92404ec  main -> main
```

### Bundle 6
## Exercise 1
```bash
PS C:\Users\HOSA.LTD\git-cafe-exercise> git checkout -b ft/menu
Switched to a new branch 'ft/menu'
PS C:\Users\HOSA.LTD\git-cafe-exercise> git add .
PS C:\Users\HOSA.LTD\git-cafe-exercise> git commit -m "add menu"
[ft/menu dce79f4] add menu
 1 file changed, 18 insertions(+)
 create mode 100644 menu.html
PS C:\Users\HOSA.LTD\git-cafe-exercise> git push
fatal: The current branch ft/menu has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/menu

To have this happen automatically for branches without a tracking      
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\HOSA.LTD\git-cafe-exercise> git push --set-upstream origin ft/menu
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 464 bytes | 464.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.   
remote: 
remote: Create a pull request for 'ft/menu' on GitHub by visiting:     
remote:      https://github.com/berniceu/git-cafe-exercise/pull/new/ft/menu
remote:
To https://github.com/berniceu/git-cafe-exercise.git
 * [new branch]      ft/menu -> ft/menu
branch 'ft/menu' set up to track 'origin/ft/menu'.
```