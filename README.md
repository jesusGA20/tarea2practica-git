# Tarea 2, Practica Git

## Jesús Gómez Albarracín
## Lenguajes de marcas y sistemas de gestión de información
## IES Aguadulce
## 1ºDAW
# 

Uso de Git mediante la terminal git bash. Las instrucciones y sus resultados deben mostrar como
bloques de código markdown:

### Creación del repositorio en nuestro ordenador (init)
```
maniana@DAMDAW1-09 MINGW64 ~/Desktop/tarea2practica-git
$ git init
Initialized empty Git repository in C:/Users/maniana/Desktop/tarea2practica-git/.git/
```
### Creación de un commit inicial (add, status, commit, log)
```
maniana@DAMDAW1-09 MINGW64 ~/Desktop/tarea2practica-git (master)
$ git add .

maniana@DAMDAW1-09 MINGW64 ~/Desktop/tarea2practica-git (master)
$ git status 
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


maniana@DAMDAW1-09 MINGW64 ~/Desktop/tarea2practica-git (master)
$ git commit -m "añado documentacion"
[master (root-commit) a424fdb] añado documentacion
 1 file changed, 40 insertions(+)
 create mode 100644 README.md

maniana@DAMDAW1-09 MINGW64 ~/Desktop/tarea2practica-git (master)
$ git log
commit a424fdb1867283234adfeda8ceee2abba1034ac5 (HEAD -> master)
Author: repaso <repaso@lmsgi.edu>
Date:   Mon Jan 15 08:43:17 2024 +0100

    añado documentacion
```
### Creación del repositorio en Github
![creo repositorio](capturas-tarea/creacion-repositorio.png)
![añado al profesor](capturas-tarea/añado%20al%20profe.png)

### Añadir el remoto al repositorio local (branch, remote)
```
maniana@DAMDAW1-09 MINGW64 ~/Desktop/tarea2practica-git (master)
$ git remote add origin https://github.com/jesusGA20/tarea2practica-git.git

maniana@DAMDAW1-09 MINGW64 ~/Desktop/tarea2practica-git (master)
$ git remote -v
origin  https://github.com/jesusGA20/tarea2practica-git.git (fetch)
origin  https://github.com/jesusGA20/tarea2practica-git.git (push)

maniana@DAMDAW1-09 MINGW64 ~/Desktop/tarea2practica-git (master)
$ git branch -v
* master a424fdb añado documentacion

```
### Subir el repositorio a Github (push) 
```

```
### Comprobar que está subido a Github
```

```