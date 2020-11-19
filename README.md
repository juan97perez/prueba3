Primero lo he clonado y luego lo he modificado hecho un commit y un push.

# prueba3
Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa
$ git clone https://github.com/juan97perez/prueba3.git
Cloning into 'prueba3'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.




Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/prueba3 (master)
$ git init
Reinitialized existing Git repository in C:/Users/Juanma/Desktop/CarpetaCasa/prueba3/.git/

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/prueba3 (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/prueba3 (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   practica3.txt

no changes added to commit (use "git add" and/or "git commit -a")

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/prueba3 (master)
$ git add *

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/prueba3 (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   practica3.txt


Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/prueba3 (master)
$ git commit -m "practica commit"
[master 3845f25] practica commit
 1 file changed, 1 insertion(+), 1 deletion(-)

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/prueba3 (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/prueba3 (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/juan97perez/prueba3.git'

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/prueba3 (master)
$ git push -u origin main https://github.com/juan97perez/prueba3.git
fatal: invalid refspec 'https://github.com/juan97perez/prueba3.git'

Juanma@DESKTOP-GIIIDH8 MINGW64 ~/Desktop/CarpetaCasa/prueba3 (master)
$ git push https://github.com/juan97perez/prueba3 master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 275 bytes | 275.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/juan97perez/prueba3
   2594209..3845f25  master -> master

Juanma@DESKTOP-GII
