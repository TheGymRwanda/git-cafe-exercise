# git-cafe-exercise

# Bundle 5

## Exercise 2

```shell
~/IdeaProjects/the-gym git:[main]
git clone https://github.com/TheGymRwanda/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 93 (from 1)
Receiving objects: 100% (107/107), 1.95 MiB | 3.46 MiB/s, done.
Resolving deltas: 100% (5/5), done.
Checking connectivity... done.

~/IdeaProjects/the-gym/git-cafe-exercise git:[main]
git add index.html

~/IdeaProjects/the-gym/git-cafe-exercise git:[main]
git commit -m "Change 'Welcome to our place' to 'Welcome to our restaurant'"

[main d7411ad] Change 'Welcome to our place' to 'Welcome to our restaurant'
 1 file changed, 2 insertions(+), 2 deletions(-)
 
~/IdeaProjects/the-gym/git-cafe-exercise git:[main]
git push origin main
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 346 bytes | 0 bytes/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/tavongamatikiti/git-cafe-exercise.git
   d1d3f9c..d7411ad  main -> main
```

# Bundle 6

## Exercise 1

```shell
~/IdeaProjects/the-gym/git-cafe-exercise git:[main]
git checkout -b feature/menu-page
Switched to a new branch 'feature/menu-page'

~/IdeaProjects/the-gym/git-cafe-exercise git:[feature/menu-page]
touch menu.html

~/IdeaProjects/the-gym/git-cafe-exercise git:[feature/menu-page]
git add menu.html

~/IdeaProjects/the-gym/git-cafe-exercise git:[feature/menu-page]
git commit -m "Add menu.html with the list of menu items"
[feature/menu-page 07dc9f6] Add menu.html with the list of menu items
 1 file changed, 47 insertions(+)
 create mode 100644 menu.html
 
~/IdeaProjects/the-gym/git-cafe-exercise git:[feature/menu-page]
git push --set-upstream origin feature/menu-page
Branch feature/menu-page set up to track remote branch feature/menu-page from origin.
Everything up-to-date
```

## Exercise 2

```shell
~/IdeaProjects/the-gym/git-cafe-exercise git:[feature/menu-page]
git checkout main
Switched to branch 'main'
Your branch is up-to-date with 'origin/main'.

~/IdeaProjects/the-gym/git-cafe-exercise git:[main]
git checkout -b fix/bug-fix
Switched to a new branch 'fix/bug-fix'

~/IdeaProjects/the-gym/git-cafe-exercise git:[fix/bug-fix]
git add index-4.html

~/IdeaProjects/the-gym/git-cafe-exercise git:[fix/bug-fix]
git commit -m 'Fixed bug'
[fix/bug-fix fed7da2] Fixed bug
 1 file changed, 2 insertions(+), 2 deletions(-)
 
~/IdeaProjects/the-gym/git-cafe-exercise git:[fix/bug-fix]
git push --set-upstream origin fix/bug-fix
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 298 bytes | 0 bytes/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'fix/bug-fix' on GitHub by visiting:
remote:      https://github.com/tavongamatikiti/git-cafe-exercise/pull/new/fix/bug-fix
remote: 
To https://github.com/tavongamatikiti/git-cafe-exercise.git
 * [new branch]      fix/bug-fix -> fix/bug-fix
Branch fix/bug-fix set up to track remote branch fix/bug-fix from origin.

~/IdeaProjects/the-gym/git-cafe-exercise git:[fix/bug-fix]
git checkout main
Switched to branch 'main'
Your branch is up-to-date with 'origin/main'.
```
```shell
~/IdeaProjects/the-gym/git-cafe-exercise git:[fix/bug-fix]
git checkout -b fix/contact
Switched to a new branch 'fix/contact'

~/IdeaProjects/the-gym/git-cafe-exercise git:[fix/contact]
git add index-4.html

~/IdeaProjects/the-gym/git-cafe-exercise git:[fix/contact]
git commit -m 'Fixed contact'
[fix/contact 9cf8dbd] Fixed contact
 1 file changed, 1 insertion(+), 1 deletion(-)
 
~/IdeaProjects/the-gym/git-cafe-exercise git:[fix/contact]
git push --set-upstream origin fix/contact
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 292 bytes | 0 bytes/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'fix/contact' on GitHub by visiting:
remote:      https://github.com/tavongamatikiti/git-cafe-exercise/pull/new/fix/contact
remote: 
To https://github.com/tavongamatikiti/git-cafe-exercise.git
 * [new branch]      fix/contact -> fix/contact
Branch fix/contact set up to track remote branch fix/contact from origin.
```
