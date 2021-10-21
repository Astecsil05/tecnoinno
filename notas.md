# Apuntes

Estos son apuntes de trabajos.

## git

Para descargar nuevos cambios: `git pull origin main`
Para agregar archivos y/o carpetas a la rama de trabajo: `git add archivo1 archivo2 archivo3 etc`
Para ver el estado de la rama de trabajo: `git status`
Para escribir una historia con lo que hay en la rama de trabajo: `git commit -m "Mi mensaje aqui"`
Para enviar mis historias(commits) a otro repositorio: `git push origin main`

git remote rename origin upstream

## ¿Como crear una carpeta desde CDM?
1. Abrir el programa Simbolo de Sistema o CMD.
2. Tipear el comando cd Descktop o cd Escritorio.
3. Tipear el siguiente comando mkdir o md (add the name you want).

## Para agg el directorio.
1. Abrimos Windows terminal.
2. Seleccionamos Git Bash.
3. Tipeamos los siguientes comando en orden:
ls
cd Proyectos (ponen el nombre de su carpeta)
ls
cd tecnoinno
ls 
git status
git add 
git commit -m "Tipean el nombre del directorio que pusieron"
git push origin main 

## Para agg archivos
Primero se debe realiza en Visual Code y lo agg por mediante Windows terminal (Git hub).

## ¿Como se crea una rama para un repositorio?
Seguir los siguientes pasos:
ls
cd (Nombre de la carpeta)
ls
cd (Una extension que viene ser una carpeta a traves de la carpeta principal)
ls
git branch 
git branch (Agg el nombre de la rama que desea)
git show branch (ver las ramas que existen)
git checkout (El nombre de la rama nueva)
git status
git add (la direccion donde se encuentra el trabajo)
git commit -m (Ponga el trabajo que realizo en Visual Code)
git push origin (Nombre de la rama nueva)
git checkout (Nombre de la rama principial que desea poner)
git branch -D (Nombre de la rama)