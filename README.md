jarad@Paula MINGW64 ~
$ git --version
git version 2.39.1.windows.1

jarad@Paula MINGW64 ~
$ git config --global user.name
Paurinya

jarad@Paula MINGW64 ~
$ git config --global user.email
paulajara@ginebro.cat

jarad@Paula MINGW64 ~
$ git config --global user.name "paurinya"

jarad@Paula MINGW64 ~
$ git config --global user.email "paulajara@ginebro.cat"

jarad@Paula MINGW64 /c
$ mkdir SMX2-2022-2023

jarad@Paula MINGW64 /c
$ cd /c/SMX2-2022-2023/

jarad@Paula MINGW64 /c/SMX2-2022-2023
$ mkdir MP07

jarad@Paula MINGW64 /c/SMX2-2022-2023
$ cd MP07

jarad@Paula MINGW64 ~
$ cd /c/SMX2-2022-2023/MP07

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07
$ echo "# jara-A015U" >> README.md

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07
$ git init
Initialized empty Git repository in C:/SMX2-2022-2023/MP07/.git/

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07 (main)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07 (main)
$ git commit -m "first commit"
[main (root-commit) 950d6d7] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07 (main)
$ git remote add origin https://github.com/Paurinya/jara-A015U.git              
jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07 (main)
$ git push -u origin main
To https://github.com/Paurinya/jara-A015U.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Paurinya/jara-A015U.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07 (main)
$ pwd
/c/SMX2-2022-2023/MP07

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07 (main)
$ mkdir jara-A015U

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07 (main)
$ cd jara-A015U/

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ echo "# jara-A015U" >> README.md

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ ls -la
total 1
drwxr-xr-x 1 jarad 197609  0 Feb  9 10:29 ./
drwxr-xr-x 1 jarad 197609  0 Feb  9 10:27 ../
-rw-r--r-- 1 jarad 197609 13 Feb  9 10:29 README.md

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git init
Initialized empty Git repository in C:/SMX2-2022-2023/MP07/jara-A015U/.git/

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ ls -la
total 5
drwxr-xr-x 1 jarad 197609  0 Feb  9 10:30 ./
drwxr-xr-x 1 jarad 197609  0 Feb  9 10:27 ../
drwxr-xr-x 1 jarad 197609  0 Feb  9 10:32 .git/
-rw-r--r-- 1 jarad 197609 13 Feb  9 10:29 README.md

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ ls -la .git
total 11
drwxr-xr-x 1 jarad 197609   0 Feb  9 10:32 ./
drwxr-xr-x 1 jarad 197609   0 Feb  9 10:30 ../
-rw-r--r-- 1 jarad 197609  21 Feb  9 10:30 HEAD
-rw-r--r-- 1 jarad 197609 112 Feb  9 10:30 config
-rw-r--r-- 1 jarad 197609  73 Feb  9 10:30 description
drwxr-xr-x 1 jarad 197609   0 Feb  9 10:30 hooks/
drwxr-xr-x 1 jarad 197609   0 Feb  9 10:30 info/
drwxr-xr-x 1 jarad 197609   0 Feb  9 10:30 objects/
drwxr-xr-x 1 jarad 197609   0 Feb  9 10:30 refs/

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ code hora_01.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ ls -la
total 6
drwxr-xr-x 1 jarad 197609   0 Feb  9 10:42 ./
drwxr-xr-x 1 jarad 197609   0 Feb  9 10:27 ../
drwxr-xr-x 1 jarad 197609   0 Feb  9 10:32 .git/
-rw-r--r-- 1 jarad 197609  13 Feb  9 10:29 README.md
-rw-r--r-- 1 jarad 197609 280 Feb  9 10:42 hora_01.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        hora_01.html

nothing added to commit but untracked files present (use "git add" to track)

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git add hora_01.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   hora_01.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git commit -m
error: switch `m' requires a value

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git commit -m "afegim hora_01.html"
[main (root-commit) 8cc21d8] afegim hora_01.html
 1 file changed, 12 insertions(+)
 create mode 100644 hora_01.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git log
commit 8cc21d847c5b4e17572d81bcc7162242d584734a (HEAD -> main)
Author: paurinya <paulajara@ginebro.cat>
Date:   Thu Feb 9 11:46:40 2023 +0100

    afegim hora_01.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git log --oneline
8cc21d8 (HEAD -> main) afegim hora_01.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git ls-tree --name-only -r 8cc21d8
hora_01.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ ls -la
total 6
drwxr-xr-x 1 jarad 197609   0 Feb  9 10:42 ./
drwxr-xr-x 1 jarad 197609   0 Feb  9 10:27 ../
drwxr-xr-x 1 jarad 197609   0 Feb  9 11:50 .git/
-rw-r--r-- 1 jarad 197609  13 Feb  9 10:29 README.md
-rw-r--r-- 1 jarad 197609 280 Feb  9 10:42 hora_01.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ code hora_01.js

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ ls -la
total 14
drwxr-xr-x 1 jarad 197609   0 Feb 10 16:18 ./
drwxr-xr-x 1 jarad 197609   0 Feb  9 10:27 ../
drwxr-xr-x 1 jarad 197609   0 Feb 10 16:11 .git/
-rw-r--r-- 1 jarad 197609  13 Feb  9 10:29 README.md
-rw-r--r-- 1 jarad 197609 280 Feb  9 10:42 hora_01.html
-rw-r--r-- 1 jarad 197609 762 Feb 10 16:18 hora_01.js

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        hora_01.js

nothing added to commit but untracked files present (use "git add" to track)

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git add hora_01.js

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   hora_01.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ code hora_02.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ ls -la
total 15
drwxr-xr-x 1 jarad 197609   0 Feb 10 16:37 ./
drwxr-xr-x 1 jarad 197609   0 Feb  9 10:27 ../
drwxr-xr-x 1 jarad 197609   0 Feb 10 16:27 .git/
-rw-r--r-- 1 jarad 197609  13 Feb  9 10:29 README.md
-rw-r--r-- 1 jarad 197609 280 Feb  9 10:42 hora_01.html
-rw-r--r-- 1 jarad 197609 762 Feb 10 16:18 hora_01.js
-rw-r--r-- 1 jarad 197609 393 Feb 10 16:37 hora_02.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        hora_02.html

nothing added to commit but untracked files present (use "git add" to track)

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git add hora_02.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   hora_02.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md


jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git commit -m "afegim hora_01.html"
[main 90b23e0] afegim hora_01.html
 1 file changed, 12 insertions(+)
 create mode 100644 hora_02.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git log
commit 90b23e0b95add6f54b47f01e4bdb4c41a1147b0c (HEAD -> main)
Author: paurinya <paulajara@ginebro.cat>
Date:   Fri Feb 10 16:40:10 2023 +0100

    afegim hora_01.html

commit dbdd48038e81d7839e1a2b0526b85fdb6cd27681
Author: paurinya <paulajara@ginebro.cat>
Date:   Fri Feb 10 16:26:27 2023 +0100

    afegim hora_01.js

commit 8cc21d847c5b4e17572d81bcc7162242d584734a
Author: paurinya <paulajara@ginebro.cat>
Date:   Thu Feb 9 11:46:40 2023 +0100

    afegim hora_01.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git log --oneline
90b23e0 (HEAD -> main) afegim hora_01.html
dbdd480 afegim hora_01.js
8cc21d8 afegim hora_01.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git ls-tree --name-only -r 90b23e0
hora_01.html
hora_01.js
hora_02.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ ls -la
total 15
drwxr-xr-x 1 jarad 197609   0 Feb 10 16:37 ./
drwxr-xr-x 1 jarad 197609   0 Feb  9 10:27 ../
drwxr-xr-x 1 jarad 197609   0 Feb 10 16:43 .git/
-rw-r--r-- 1 jarad 197609  13 Feb  9 10:29 README.md
-rw-r--r-- 1 jarad 197609 280 Feb  9 10:42 hora_01.html
-rw-r--r-- 1 jarad 197609 762 Feb 10 16:18 hora_01.js
-rw-r--r-- 1 jarad 197609 393 Feb 10 16:37 hora_02.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ code hora_02.js

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ ls -la
total 19
drwxr-xr-x 1 jarad 197609   0 Feb 10 16:46 ./
drwxr-xr-x 1 jarad 197609   0 Feb  9 10:27 ../
drwxr-xr-x 1 jarad 197609   0 Feb 10 16:45 .git/
-rw-r--r-- 1 jarad 197609  13 Feb  9 10:29 README.md
-rw-r--r-- 1 jarad 197609 280 Feb  9 10:42 hora_01.html
-rw-r--r-- 1 jarad 197609 762 Feb 10 16:18 hora_01.js
-rw-r--r-- 1 jarad 197609 393 Feb 10 16:37 hora_02.html
-rw-r--r-- 1 jarad 197609 729 Feb 10 16:46 hora_02.js

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        hora_02.js

nothing added to commit but untracked files present (use "git add" to track)

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git add hora_02.js

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   hora_02.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md


jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git commit -m "afegim hora_02.js"
[main 0d67081] afegim hora_02.js
 1 file changed, 19 insertions(+)
 create mode 100644 hora_02.js
jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git log
commit 0d670816f8c8032a3a118ae2fa18e66ba35ec8d7 (HEAD -> main)
Author: paurinya <paulajara@ginebro.cat>
Date:   Fri Feb 10 16:48:29 2023 +0100

    afegim hora_02.js

commit 90b23e0b95add6f54b47f01e4bdb4c41a1147b0c
Author: paurinya <paulajara@ginebro.cat>
Date:   Fri Feb 10 16:40:10 2023 +0100

    afegim hora_01.html

commit dbdd48038e81d7839e1a2b0526b85fdb6cd27681
Author: paurinya <paulajara@ginebro.cat>
Date:   Fri Feb 10 16:26:27 2023 +0100

    afegim hora_01.js

commit 8cc21d847c5b4e17572d81bcc7162242d584734a
Author: paurinya <paulajara@ginebro.cat>
Date:   Thu Feb 9 11:46:40 2023 +0100

    afegim hora_01.html
:
jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git log --oneline
0d67081 (HEAD -> main) afegim hora_02.js
90b23e0 afegim hora_01.html
dbdd480 afegim hora_01.js
8cc21d8 afegim hora_01.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git ls-tree --name-only -r 0d67081
hora_01.html
hora_01.js
hora_02.html
hora_02.js

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ code hora_03.js

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ ls -la
total 24
drwxr-xr-x 1 jarad 197609    0 Feb 10 17:06 ./
drwxr-xr-x 1 jarad 197609    0 Feb  9 10:27 ../
drwxr-xr-x 1 jarad 197609    0 Feb 10 16:56 .git/
-rw-r--r-- 1 jarad 197609   13 Feb  9 10:29 README.md
-rw-r--r-- 1 jarad 197609  280 Feb  9 10:42 hora_01.html
-rw-r--r-- 1 jarad 197609  762 Feb 10 16:18 hora_01.js
-rw-r--r-- 1 jarad 197609  393 Feb 10 16:37 hora_02.html
-rw-r--r-- 1 jarad 197609  729 Feb 10 16:46 hora_02.js
-rw-r--r-- 1 jarad 197609  517 Feb 10 16:52 hora_03.html
-rw-r--r-- 1 jarad 197609 1087 Feb 10 17:06 hora_03.js

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        hora_03.js

nothing added to commit but untracked files present (use "git add" to track)

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git add hora_03.js

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   hora_03.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md


jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git commit -m "afegim hora_03.js"
[main aaaed60] afegim hora_03.js
 1 file changed, 31 insertions(+)
 create mode 100644 hora_03.js

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git log
commit aaaed60a987477ed476c4734ee4d5eeb3dd959dc (HEAD -> main)
Author: paurinya <paulajara@ginebro.cat>
Date:   Fri Feb 10 17:07:21 2023 +0100

    afegim hora_03.js

commit 5649011813402234be1d575ddccea5773b21d0a7
Author: paurinya <paulajara@ginebro.cat>
Date:   Fri Feb 10 16:56:29 2023 +0100

    afegim hora_03.html

commit 0d670816f8c8032a3a118ae2fa18e66ba35ec8d7
Author: paurinya <paulajara@ginebro.cat>
Date:   Fri Feb 10 16:48:29 2023 +0100

    afegim hora_02.js

commit 90b23e0b95add6f54b47f01e4bdb4c41a1147b0c
Author: paurinya <paulajara@ginebro.cat>
Date:   Fri Feb 10 16:40:10 2023 +0100

    afegim hora_01.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git log --oneline
aaaed60 (HEAD -> main) afegim hora_03.js
5649011 afegim hora_03.html
0d67081 afegim hora_02.js
90b23e0 afegim hora_01.html
dbdd480 afegim hora_01.js
8cc21d8 afegim hora_01.html

jarad@Paula MINGW64 /c/SMX2-2022-2023/MP07/jara-A015U (main)
$ git ls-tree --name-only -r aaaed60
hora_01.html
hora_01.js
hora_02.html
hora_02.js
hora_03.html
hora_03.js
