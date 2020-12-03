# GitEjemploExamen
######Briggit@Briggitte MINGW64 ~/Desktop#######
**$ git clone https://github.com/Briggitte5/GitEjemploExamen.git
Cloning into 'GitEjemploExamen'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.**

Briggit@Briggitte MINGW64 ~/Desktop
$ cd GitEjemploExamen

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git add -A

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   dos.txt
        new file:   tres.txt
        new file:   uno.txt


Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git tag imagen

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   dos.txt
        new file:   tres.txt
        new file:   uno.txt


Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git tag txtMola

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   dos.txt
        new file:   tres.txt
        new file:   uno.txt


Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git commit -m "subida a la nube"
[main 6fb3aa2] subida a la nube
 3 files changed, 3 insertions(+)
 create mode 100644 dos.txt
 create mode 100644 tres.txt
 create mode 100644 uno.txt

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (5/5), 394 bytes | 98.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Briggitte5/GitEjemploExamen.git
   a188908..6fb3aa2  main -> main

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git pull
Already up to date.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git branch Rama1

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git log
commit 6fb3aa2cbc7edb9af82dc98d09c69f2e0fe9a6f9 (HEAD -> main, origin/main, origin/HEAD, Rama1)
Author: briggit <briggittearellano5@gmail.com>
Date:   Tue Nov 24 15:55:45 2020 +0100

    subida a la nube

commit a188908bd79f6e9c57eb35b4e7b4343687becdfc (tag: txtMola, tag: imagen)
Author: Briggitte5 <73605166+Briggitte5@users.noreply.github.com>
Date:   Tue Nov 24 15:11:04 2020 +0100

    Initial commit

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git push
Everything up-to-date

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git push --set-upstream origin Rama1
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'Rama1' on GitHub by visiting:
remote:      https://github.com/Briggitte5/GitEjemploExamen/pull/new/Rama1
remote:
To https://github.com/Briggitte5/GitEjemploExamen.git
 * [new branch]      Rama1 -> Rama1
Branch 'Rama1' set up to track remote branch 'Rama1' from 'origin'.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git push --set-upstream origin txtMola
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Briggitte5/GitEjemploExamen.git
 * [new tag]         txtMola -> txtMola

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git branch
  Rama1
* main

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git checkout Rama1
Switched to branch 'Rama1'
Your branch is up to date with 'origin/Rama1'.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git add -A

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git status
On branch Rama1
Your branch is up to date with 'origin/Rama1'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   cuatro.txt


Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git commit -m "subida a la nube"
[Rama1 06f5a44] subida a la nube
 1 file changed, 1 insertion(+)
 create mode 100644 cuatro.txt

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git status
On branch Rama1
Your branch is ahead of 'origin/Rama1' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 276 bytes | 138.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Briggitte5/GitEjemploExamen.git
   6fb3aa2..06f5a44  Rama1 -> Rama1

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git branch Rama2

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ ^C

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git checkout Rama1
Already on 'Rama1'
Your branch is up to date with 'origin/Rama1'.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git branch Rama2
fatal: A branch named 'Rama2' already exists.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git checkout Rama1
Switched to branch 'Rama1'
Your branch is up to date with 'origin/Rama1'.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git branch -D "Rama2"
Deleted branch Rama2 (was 06f5a44).

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git branch Rama2

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git log
commit 6fb3aa2cbc7edb9af82dc98d09c69f2e0fe9a6f9 (HEAD -> main, origin/main, origin/HEAD, Rama2)
Author: briggit <briggittearellano5@gmail.com>
Date:   Tue Nov 24 15:55:45 2020 +0100

    subida a la nube

commit a188908bd79f6e9c57eb35b4e7b4343687becdfc (tag: txtMola, tag: imagen)
Author: Briggitte5 <73605166+Briggitte5@users.noreply.github.com>
Date:   Tue Nov 24 15:11:04 2020 +0100

    Initial commit

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git push
Everything up-to-date

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git push --set-upstream origin Rama2
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'Rama2' on GitHub by visiting:
remote:      https://github.com/Briggitte5/GitEjemploExamen/pull/new/Rama2
remote:
To https://github.com/Briggitte5/GitEjemploExamen.git
 * [new branch]      Rama2 -> Rama2
Branch 'Rama2' set up to track remote branch 'Rama2' from 'origin'.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git branch -D "Rama2"
Deleted branch Rama2 (was 6fb3aa2).

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git push
Everything up-to-date

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git pull
From https://github.com/Briggitte5/GitEjemploExamen
 * [new tag]         Releasetxt1.0 -> Releasetxt1.0
Already up to date.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git commit -m "subida a la nube"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git push
Everything up-to-date

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git push --set-upstream origin main
Everything up-to-date
Branch 'main' set up to track remote branch 'main' from 'origin'.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git push --delete "Rama2"
fatal: --delete doesn't make sense without any refs

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git checkout Rama1
Switched to branch 'Rama1'
Your branch is up to date with 'origin/Rama1'.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git merge main
Already up to date.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git push
Everything up-to-date

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git pull
Already up to date.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git push --set-upstream origin Rama1
Everything up-to-date
Branch 'Rama1' set up to track remote branch 'Rama1' from 'origin'.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git status
On branch Rama1
Your branch is up to date with 'origin/Rama1'.

nothing to commit, working tree clean

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git log
commit 06f5a442f6072928abef9a9f02649a4542a65a19 (HEAD -> Rama1, origin/Rama1)
Author: briggit <briggittearellano5@gmail.com>
Date:   Tue Nov 24 16:09:57 2020 +0100

    subida a la nube

commit 6fb3aa2cbc7edb9af82dc98d09c69f2e0fe9a6f9 (tag: Releasetxt1.0, origin/main, origin/Rama2, origin/HEAD, main)
Author: briggit <briggittearellano5@gmail.com>
Date:   Tue Nov 24 15:55:45 2020 +0100

    subida a la nube

commit a188908bd79f6e9c57eb35b4e7b4343687becdfc (tag: txtMola, tag: imagen)
Author: Briggitte5 <73605166+Briggitte5@users.noreply.github.com>
Date:   Tue Nov 24 15:11:04 2020 +0100

    Initial commit

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git commit -m "sudida a la nube"
On branch Rama1
Your branch is up to date with 'origin/Rama1'.

nothing to commit, working tree clean

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git push
Everything up-to-date

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (Rama1)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git commit -m "subido a la nube"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$ git push
Everything up-to-date

Briggit@Briggitte MINGW64 ~/Desktop/GitEjemploExamen (main)
$
