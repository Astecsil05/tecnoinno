# Estos son apuntes de trabajos.

## En la shell

## ¿Como crear una carpeta?

`mkdir nombre` (donde `nombre` es el nombre de la carpeta).

## En git

- Para descargar nuevos cambios: `git pull main`
- Para agregar archivos y/o carpetas a la rama de trabajo: `git add Semana1 Semana2 Semana3 etc`
- Para ver el estado de la rama de trabajo: `git status`
- Para escribir una historiRutina con lo que hay en la rama de trabajo: `git commit -m "Mi mensaje aqui"`
- Para enviar mis Rutinas (commits) a otro repositorio: `git push origin main`
- Para cambiar el nombre a un *apuntador* `git remote rename nombre nuevo_nombre`

## Para Agregar Carpetas o Archivos al arbol de trabajo en la rama actual

`git add nombre` donde *nombre* puede ser archivos y/o carpetas


## ¿Cómo se crea una rama?

`git branch nombre`  donde *nombre* es el nombre de la nueva rama que se creará.

## ¿Cómo se crea una rama y también moverse para trabajar en esa rama?

Se puede *crear* e ir a la nueva rama creada usando un solo comando: `git checkout -b nombre` donde *nombre* es el nombre de la nueva rama que se creará.

## Para hacer cambios en una rama
git checkout -b arreglos