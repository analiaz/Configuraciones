# Creacion de un repositorio 
	`git init`
# Seguimiento del estado de un archivo
	`git status`
# Agregar un archivo 
	`git add nombre_archivo`
# Para que se guarde correctamente los cambios 
	`git commit -m "se agrego tal cosa"`
# Subir el repositorio a github

1.Se debe crear un repositorio en github y obtener su URL, luego se ejecuta en consola el comando 
	`git remote add origin <URL>` 

2.Se lo sube a github  
	`git push -u origin master`

#Para ver los repositorio configurados en el sistema
	`git remote -v`
#Para acceder a informacion de repositorios remotos
	`git fetch`
#Para la actualizacion de un archivo con muchos commits:
* sin querer que se vean los cambios y master que pase a apuntar directamente al ultimo commit  
	`git rebase -p nombreDeOtroRepositorio/master`
* mostrando los cambioso
	`git merge`
# si se quiere desviar archivos que no interesan subir a gitHub se utiliza
	`echo 'nombreArchivo o nombre directorio' >> .gitgnore`
