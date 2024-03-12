# belajarGIT

Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT
Rafael@LAPTOP-6BB3ED55 MINGW64 ~
$ pwd
/c/Users/Rafael

Rafael@LAPTOP-6BB3ED55 MINGW64 ~
$ cd PEMOGRAMANWEB

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB
$ cd Tugas

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas (master)
$ git clone https://github.com/trplerr/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas (master)
$ cd BelajarGIT

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git branch Tugas-git

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-git)
$ touch Tugas-git.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-git)
$ git add Tugas-git.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-git)
$  git commit -m "Menambahkan file Tugas-git.txt"
[Tugas-git ac1ed5e] Menambahkan file Tugas-git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-git)
$  git add Tugas-git.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-git)
$ git commit -m "Menambahkan perubahan pada Tugas-git.txt"
[Tugas-git b88e2c8] Menambahkan perubahan pada Tugas-git.txt
 1 file changed, 2 insertions(+)

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git merge Tugas-git Updating
merge: Updating - not something we can merge

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$  git merge Tugas-git
Updating edfe667..b88e2c8
Fast-forward
 Tugas-git.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-git.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 576 bytes | 576.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/trplerr/belajarGIT.git
   edfe667..b88e2c8  main -> main

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git branch Tugas-html

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-html)
$  touch Tugas-html.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-html)
$ git add Tugas-html.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html 8efc4da] Menambahkan file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-html)
$ git add Tugas-html.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html 5791449] Menambahkan file Tugas-html.txt
 1 file changed, 2 insertions(+)

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git merge Tugas-html
Updating b88e2c8..5791449
Fast-forward
 Tugas-html.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-html.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 551 bytes | 551.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/trplerr/belajarGIT.git
   b88e2c8..5791449  main -> main

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git branch Tugas-css

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-css)
$  touch Tugas-css.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-css)
$  git add Tugas-css.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css 226356c] Menambahkan file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-css)
$ git add Tugas-css.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css 5d2fb4e] Menambahkan file Tugas-css.txt
 1 file changed, 2 insertions(+)

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git merge Tugas-css
Updating 5791449..5d2fb4e
Fast-forward
 Tugas-css.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-css.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 586 bytes | 586.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git branch Tugas-js

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$  git checkout Tugas-js
Switched to branch 'Tugas-js'

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-js)
$ touch Tugas-js.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-js)
$ git add Tugas-js.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js b92b940] Menambahkan file Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-js)
$ git add Tugas-js.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js 37f2264] Menambahkan file Tugas-js.txt
 1 file changed, 2 insertions(+)

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git merge Tugas-js
Updating 5d2fb4e..37f2264
Fast-forward
 Tugas-js.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-js.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 517 bytes | 517.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/trplerr/belajarGIT.git
   5d2fb4e..37f2264  main -> main

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git branch Tugas-midProject

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 797ed3a] Menambahkan file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 0389cff] Menambahkan file Tugas-midProject.txt
 1 file changed, 2 insertions(+)

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git merge Tugas-midProject
Updating 37f2264..0389cff
Fast-forward
 Tugas-midProject.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-midProject.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$  git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 549 bytes | 549.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/trplerr/belajarGIT.git
   37f2264..0389cff  main -> main

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git branch Tugas-php

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-php)
$ touch Tugas-php.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-php)
$ git add Tugas-php.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php 8889cfc] Menambahkan file Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-php)
$  git add Tugas-php.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-php)
$  git add Tugas-php.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php e6f6537] Menambahkan file Tugas-php.txt
 1 file changed, 2 insertions(+)

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-php)
$  git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git merge Tugas-php
Updating 0389cff..e6f6537
Fast-forward
 Tugas-php.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-php.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 522 bytes | 522.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/trplerr/belajarGIT.git
   0389cff..e6f6537  main -> main

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$  git branch Tugas-finalProject

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$  git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-finalProject)
$  git add Tugas-finalProject.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[Tugas-finalProject 15f05d7] Menambahkan file Tugas-finalProject.txt
 1 file changed, 3 insertions(+)
 create mode 100644 Tugas-finalProject.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (Tugas-finalProject)
$  git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git merge Tugas-finalProject
Updating e6f6537..15f05d7
Fast-forward
 Tugas-finalProject.txt | 3 +++
 1 file changed, 3 insertions(+)
 create mode 100644 Tugas-finalProject.txt

Rafael@LAPTOP-6BB3ED55 MINGW64 ~/PEMOGRAMANWEB/Tugas/BelajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 334 bytes | 334.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/trplerr/belajarGIT.git
   e6f6537..15f05d7  main -> main
