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