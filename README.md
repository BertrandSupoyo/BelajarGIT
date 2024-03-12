tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiTT
BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB
$ git clone "https://github.com/BertrandSupoyo/belajarGIT.git"
Cloning into 'belajarGIT'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB
$ $ git config --global user.email "betran1092@gmail.com"
bash: $: command not found

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB
$ git config --global user.email "betran1092@gmail.com"

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB
$ cd belajarGIT

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-git)
$ git add Tugas-git.txt


BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-git)
$ git commit -m "commit 1 tambah tugasgit dan keterangan"
[Tugas-git b10ab72] commit 1 tambah tugasgit dan keterangan
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$  git merge Tugas-git
Updating 8703c13..b10ab72
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 296 bytes | 296.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/BertrandSupoyo/belajarGIT.git
   8703c13..b10ab72  main -> main

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-html)
$ git commit -m "commit 2 tambah tugasgit dan keterangan"
On branch Tugas-html
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-html.txt

nothing added to commit but untracked files present (use "git add" to track)

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-html)
$ git commit -m "commit 2 tambah tugasgit dan keterangan"
On branch Tugas-html
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-html.txt

nothing added to commit but untracked files present (use "git add" to track)

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-html)
$ git commit -m "commit 2 tambah tugasgit dan keterangan"
[Tugas-html ec8ff6b] commit 2 tambah tugasgit dan keterangan
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$  git merge Tugas-html
Updating b10ab72..ec8ff6b
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 325 bytes | 325.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/BertrandSupoyo/belajarGIT.git
   b10ab72..ec8ff6b  main -> main

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$  git merge Tugas-css
merge: Tugas-css - not something we can merge

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-css)
$ git commit -m "commit 3 tambah tugasgit dan keterangan"
[Tugas-css b40f50a] commit 3 tambah tugasgit dan keterangan
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-css)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        Tugas-css.txt
Please commit your changes or stash them before you switch branches.
Aborting

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-css)
$ git commit -m "commit 3 tambah tugasgit dan keterangan"
[Tugas-css 61988f4] commit 3 tambah tugasgit dan keterangan
 1 file changed, 1 insertion(+)

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$  git merge Tugas-css
Updating ec8ff6b..61988f4
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 575 bytes | 575.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/BertrandSupoyo/belajarGIT.git
   ec8ff6b..61988f4  main -> main

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-js)
$ git commit -m "commit 4 tambah tugasgit dan keterangan"
[Tugas-js 544c0b7] commit 4 tambah tugasgit dan keterangan
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$  git merge Tugas-js
Updating 61988f4..544c0b7
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 288 bytes | 288.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/BertrandSupoyo/belajarGIT.git
   61988f4..544c0b7  main -> main

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-midProject)
$ git commit -m "commit 5 tambah tugasgit dan keterangan"
[Tugas-midProject b6ecf41] commit 5 tambah tugasgit dan keterangan
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$  git merge Tugas-midProject
Updating 544c0b7..b6ecf41
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 261 bytes | 261.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/BertrandSupoyo/belajarGIT.git
   544c0b7..b6ecf41  main -> main

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-php)
$ git commit -m "commit 6 tambah tugasgit dan keterangan"
[Tugas-php fce2ccc] commit 6 tambah tugasgit dan keterangan
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$  git merge Tugas-php
Updating b6ecf41..fce2ccc
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 268 bytes | 268.00 KiB/s, done.
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/BertrandSupoyo/belajarGIT.git
   b6ecf41..fce2ccc  main -> main
BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt
fatal: pathspec 'Tugas-finalProject.txt' did not match any files

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-finalProject)
$ git commit -m "commit 7 tambah tugasgit dan keterangan"
[Tugas-finalProject 7bd7aab] commit 7 tambah tugasgit dan keterangan
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$  git merge Tugas-finalProject
Updating fce2ccc..7bd7aab
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

BERTRAN@DESKTOP-N3NSVSP MINGW64 /c/WEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 249 bytes | 249.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/BertrandSupoyo/belajarGIT.git
   fce2ccc..7bd7aab  main -> main
