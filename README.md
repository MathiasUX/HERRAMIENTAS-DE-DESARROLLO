# Inicialización y configuración del repositorio HERRAMIENTAS

```bash
JANSM@LAPTOP-30GD0BVG MINGW64 /d/2025-2/Herramientas de Desarrollo/AVANCE
$ git init
Initialized empty Git repository in D:/2025-2/Herramientas de Desarrollo/AVANCE/.git/

JANSM@LAPTOP-30GD0BVG MINGW64 /d/2025-2/Herramientas de Desarrollo/AVANCE (master)
$ git config --global user.name "MoralesDominguezJansSnider"

JANSM@LAPTOP-30GD0BVG MINGW64 /d/2025-2/Herramientas de Desarrollo/AVANCE (master)
$ git config --global user.email "u22330117@utp.edu.pe"

JANSM@LAPTOP-30GD0BVG MINGW64 /d/2025-2/Herramientas de Desarrollo/AVANCE (master)
$ touch README.md

JANSM@LAPTOP-30GD0BVG MINGW64 /d/2025-2/Herramientas de Desarrollo/AVANCE (master)
$ touch .gitignore

JANSM@LAPTOP-30GD0BVG MINGW64 /d/2025-2/Herramientas de Desarrollo/AVANCE (master)
$ touch LICENSE

JANSM@LAPTOP-30GD0BVG MINGW64 /d/2025-2/Herramientas de Desarrollo/AVANCE (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        LICENSE
        README.md

nothing added to commit but untracked files present (use "git add" to track)

JANSM@LAPTOP-30GD0BVG MINGW64 /d/2025-2/Herramientas de Desarrollo/AVANCE (master)
$ git add .

JANSM@LAPTOP-30GD0BVG MINGW64 /d/2025-2/Herramientas de Desarrollo/AVANCE (master)
$ git commit -m "primer commit de configuracion"
[master (root-commit) 14c94a5] primer commit de configuracion
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 .gitignore
 create mode 100644 LICENSE
 create mode 100644 README.md

JANSM@LAPTOP-30GD0BVG MINGW64 /d/2025-2/Herramientas de Desarrollo/AVANCE (master)
$ git remote add origin https://github.com/MoralesDominguezJansSnider/HERRAMIENTAS.git

JANSM@LAPTOP-30GD0BVG MINGW64 /d/2025-2/Herramientas de Desarrollo/AVANCE (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 265 bytes | 265.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/MoralesDominguezJansSnider/HERRAMIENTAS.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.