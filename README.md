Daftar tugas / branch
  1.  Tugas-git
  2.  Tugas-html
  3.  Tugas-css
  4.  Tugas-js
  5.  Tugas-midProject
  6.  Tugas-php
  7.  Tugas-finalProject

Daftar perintah GiT
…
lenovo@LAPTOP-IPCD9QHM MINGW64 ~ (master)
$ git config --global user.email "christianandreasroeroe@gmail.com"

lenovo@LAPTOP-IPCD9QHM MINGW64 ~ (master)
$ git init
Reinitialized existing Git repository in C:/Users/lenovo/.git/

lenovo@LAPTOP-IPCD9QHM MINGW64 ~ (master)
$ cd Documents

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents (master)
$ git clone https://github.com/Reasonly40/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents (master)
$ git branch Tugas-git
fatal: not a valid object name: 'master'

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents (master)
$ cd belajarGIT

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-git

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git branch
  Tugas-git
* main

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Tambah file Tugas-git.txt"
[Tugas-git fb06332] Tambah file Tugas-git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Mengubah isi pada file Tugas-git.txt"
[Tugas-git d76319f] Mengubah isi pada file Tugas-git.txt
 1 file changed, 1 insertion(+)

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git merge Tugas-git
Already up to date.

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-git
Updating c974015..d76319f
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 589 bytes | 589.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Reasonly40/belajarGIT.git
   c974015..d76319f  main -> main

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-html

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m "Tambah file Tugas-html.txt"
[Tugas-html 9fad7e4] Tambah file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m "Mengubah isi pada file Tugas-html.txt"
[Tugas-html f5cb6ad] Mengubah isi pada file Tugas-html.txt
 1 file changed, 1 insertion(+)

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-html
Updating d76319f..f5cb6ad
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 575 bytes | 575.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Reasonly40/belajarGIT.git
   d76319f..f5cb6ad  main -> main

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-css

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m "Tambah file Tugas-css.txt"
[Tugas-css 6a4d6e6] Tambah file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m "Mengubah isi pada file Tugas-css.txt"
[Tugas-css 1de0ee1] Mengubah isi pada file Tugas-css.txt
 1 file changed, 1 insertion(+)

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-css
Updating f5cb6ad..1de0ee1
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 605 bytes | 605.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Reasonly40/belajarGIT.git
   f5cb6ad..1de0ee1  main -> main

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-js

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt
lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "Tambah file Tugas-js.txt"
[Tugas-js 6ea6cc6] Tambah file Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt
lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "Mengubah isi pada file Tugas-js.txt"
[Tugas-js 97a4c38] Mengubah isi pada file Tugas-js.txt
 1 file changed, 1 insertion(+)

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-js
Updating 1de0ee1..97a4c38
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 535 bytes | 535.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Reasonly40/belajarGIT.git
   1de0ee1..97a4c38  main -> main

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-midProject

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m "Tambah file Tugas-midProject.txt"
[Tugas-midProject 0e55cc0] Tambah file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m "Mengubah isi pada file Tugas-midProject.txt"
[Tugas-midProject a5441e2] Mengubah isi pada file Tugas-midProject.txt
 1 file changed, 1 insertion(+)

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-midProject
Updating 97a4c38..a5441e2
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 564 bytes | 564.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Reasonly40/belajarGIT.git
   97a4c38..a5441e2  main -> main

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-php

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m "Tambah file Tugas-php.txt"
[Tugas-php c560f03] Tambah file Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m "Mengubah isi pada file Tugas-php.txt"
[Tugas-php b413974] Mengubah isi pada file Tugas-php.txt
 1 file changed, 1 insertion(+)

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-php
Updating a5441e2..b413974
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 541 bytes | 541.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Reasonly40/belajarGIT.git
   a5441e2..b413974  main -> main

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-finalProject

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m "Tambah file Tugas-finalProject.txt"
[Tugas-finalProject ec7d7e4] Tambah file Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m "Mengubah isi pada file Tugas-finalProject.txt"
[Tugas-finalProject fc8933a] Mengubah isi pada file Tugas-finalProject.txt
 1 file changed, 1 insertion(+)

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-finalProject
Updating b413974..fc8933a
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

lenovo@LAPTOP-IPCD9QHM MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 562 bytes | 562.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Reasonly40/belajarGIT.git
   b413974..fc8933a  main -> main
