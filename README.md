Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
ACEL@DESKTOP-G449M5Q MINGW64 ~
$ cd D:\BelajarGit

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit
$ git clone https://github.com/MarcellinoBandule/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit
$ cd belajarGIT

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git checkout -b Tugas-Git
Switched to a new branch 'Tugas-Git'

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-Git)
$ touch Tugas-Git.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-Git)
$ git add Tugas-Git.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-Git)
$ git commit -m "add Tugas-Git.txt"
[Tugas-Git 10129fe] add Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-Git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git merge Tugas-Git
Updating 8a8fe6f..10129fe
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 306.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/MarcellinoBandule/belajarGIT.git
   8a8fe6f..10129fe  main -> main

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-html)
$ git commit -m "add Tugas-html.txt"
[Tugas-html 5f978c8] add Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git merge Tugas-html
Updating 10129fe..5f978c8
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 333 bytes | 333.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/MarcellinoBandule/belajarGIT.git
   10129fe..5f978c8  main -> main

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-css)
$ git commit -m "add Tugas-css.txt"
[Tugas-css dab6df3] add Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git merge Tugas-css
Updating 5f978c8..dab6df3
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 283 bytes | 283.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MarcellinoBandule/belajarGIT.git
   5f978c8..dab6df3  main -> main

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-js)
$

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-js)
$ git commit -m "add Tugas-js.txt"
[Tugas-js 6a6de45] add Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git merge Tugas-js
Updating dab6df3..6a6de45
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 295 bytes | 295.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MarcellinoBandule/belajarGIT.git
   dab6df3..6a6de45  main -> main

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-midProject)
$ git commit -m "add Tugas-midProject.txt"
[Tugas-midProject a53a4c0] add Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git merge Tugas-midProject
Updating 6a6de45..a53a4c0
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 313 bytes | 313.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MarcellinoBandule/belajarGIT.git
   6a6de45..a53a4c0  main -> main
ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-php)
$ git commit -m "add Tugas-php.txt"
[Tugas-php 323aa1d] add Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git merge Tugas-php
Updating a53a4c0..323aa1d
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 297 bytes | 297.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MarcellinoBandule/belajarGIT.git
   a53a4c0..323aa1d  main -> main

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-finalProject)
$ git commit -m "add Tugas-finalProject.txt"
[Tugas-finalProject d935e75] add Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 323aa1d..d935e75
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 310 bytes | 310.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MarcellinoBandule/belajarGIT.git
   323aa1d..d935e75  main -> main

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$ ^C

ACEL@DESKTOP-G449M5Q MINGW64 /d/BelajarGit/belajarGIT (main)
$
