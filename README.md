# Prueba de un repo local a remoto

**Igual se necesita crear un repo en remoto que reciba al local y luego:**

USUARIO@USUARIO-PC MINGW32 /f/MIS PROGRAMAS/GIT/PruebaX
$ git init
Initialized empty Git repository in F:/MIS PROGRAMAS/GIT/PruebaX/.git/

USUARIO@USUARIO-PC MINGW32 /f/MIS PROGRAMAS/GIT/PruebaX (master)
$ git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

USUARIO@USUARIO-PC MINGW32 /f/MIS PROGRAMAS/GIT/PruebaX (master)
$ git commit -m "Primer commit"
[master (root-commit) 96fb6c8] Primer commit
2 files changed, 2 insertions(+)
create mode 100644 .gitignore
create mode 100644 README.md

USUARIO@USUARIO-PC MINGW32 /f/MIS PROGRAMAS/GIT/PruebaX (master)
$ git branch
* master

USUARIO@USUARIO-PC MINGW32 /f/MIS PROGRAMAS/GIT/PruebaX (master)
$ git branch -M main

USUARIO@USUARIO-PC MINGW32 /f/MIS PROGRAMAS/GIT/PruebaX (main)
$ git branch
* main

USUARIO@USUARIO-PC MINGW32 /f/MIS PROGRAMAS/GIT/PruebaX (main)
$ git remote add origin https://github.com/edriveral/pruebaX.git

USUARIO@USUARIO-PC MINGW32 /f/MIS PROGRAMAS/GIT/PruebaX (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 278 bytes | 278.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/edriveral/pruebaX.git
* [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
