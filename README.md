# git-cafe-exercise
1. Bundle 5 Exercise 2
- Fork this project https://github.com/TheGymRwanda/git-cafe-exercise
- Clone your fork on your machine
- Edit the `index.html` file
- Change the text `Welcome to our place` to `Welcome to our restaurant`
- Commit and push the changes
- Raise a PR to the original Repo

Solution:
``` bash
jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exerc
ise$ git add --all
jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$ git reset
Unstaged changes after reset:
M       README.md
M       css/camera.css
M       css/contact-form.css
M       css/google-map.css
M       css/grid.css
M       css/style.css
M       index.html
jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$
 git add index.html 
jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$
 git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   css/camera.css
        modified:   css/contact-form.css
        modified:   css/google-map.css
        modified:   css/grid.css
        modified:   css/style.css

jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$
 git commit -m "changed content in the index"
[main d296d18] changed content in the index
 1 file changed, 1 insertion(+), 1 deletion(-)
jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$
 git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 329 bytes | 47.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.  
To https://github.com/sjamillah/git-cafe-exercise.git
   d1d3f9c..d296d18  main -> main
```
2. Bundle 6 Exercise 1
- On the `git-cafe-exercise` repo create a new feature branch
- Add new changes related to a new page named `Menu`
- Afterward, raise a new PR
- Request review

Solution:
``` bash
jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$
 git checkout -b feature
Switched to a new branch 'feature'
jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$ git add --all
jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$ git commit -m "menu of the restaurant"
[feature 50843cf] menu of the restaurant
 6 files changed, 2182 insertions(+), 2093 deletions(-)
 create mode 100644 menu.html
jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$ git push
fatal: The current branch feature has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin feature

jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$
 git push --set-upstream origin feature
Enumerating objects: 16, done.
Counting objects: 100% (16/16), done.
Delta compression using up to 8 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (9/9), 8.83 KiB | 273.00 KiB/s, done.
Total 9 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.  
remote:
remote: Create a pull request for 'feature' on GitHub by visiting:     
remote:      https://github.com/sjamillah/git-cafe-exercise/pull/new/feature
remote:
To https://github.com/sjamillah/git-cafe-exercise.git
 * [new branch]      feature -> feature
Branch 'feature' set up to track remote branch 'feature' from 'origin'.
```
3. Bundle 6 Exercise 2
- Create a new bug fix branch
- From there change the title of the `index-4.html` file to “**Contact**”
- Raise a new PR
- Request review

Solution:
``` bash
jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$
 git checkout -b bug/fix
Switched to a new branch 'bug/fix'
jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$ git add index-4.html 
jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$ git commit -m "changed the title from Menu to Contact"
[bug/fix d7230f3] changed the title from Menu to Contact
 1 file changed, 1 insertion(+), 1 deletion(-)
jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$ git push
fatal: The current branch bug/fix has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin bug/fix

jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$
 git push --set-upstream origin bug/fix
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 319 bytes | 63.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.  
remote:
remote: Create a pull request for 'bug/fix' on GitHub by visiting:     
remote:      https://github.com/sjamillah/git-cafe-exercise/pull/new/bug/fix
remote:
To https://github.com/sjamillah/git-cafe-exercise.git
 * [new branch]      bug/fix -> bug/fix
Branch 'bug/fix' set up to track remote branch 'bug/fix' from 'origin'.
jamillah@DESKTOP-533N1K0:/mnt/c/Users/LENOVO/Desktop/git-cafe-exercise$
 git pull
remote: Enumerating objects: 1, done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 1 (from 1)  
Unpacking objects: 100% (1/1), 920 bytes | 70.00 KiB/s, done.
From https://github.com/sjamillah/git-cafe-exercise
   a87212f..18fa35c  main       -> origin/main
Already up to date.
```