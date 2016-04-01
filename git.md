# Creacion de un repositorio 
	`git init`
# Seguimiento del estado de un archivo
	`git status`
# Agregar un archivo 
	`git add nombre_archivo`
# Para que se guarde correctamente los cambios 
	`git commit -m "se agrego tal cosa"`
# Subir el repositorio a github
Primero se debe crear un repositorio en github y obtener su URL, luego se ejecuta en consola el comando 
	`git remote add origin <URL>` 
Segundo se lo sube a github con el comando 
	`git push -u origin master`
#Si el repositorio ya existe 
Si se hicieron nuevos cambios en el archivo y se quieren subir para tener todo actualizado, luego de hacer commit solo se debe usar
	`git push -u origin master`
