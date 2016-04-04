# Configuracion general
Para crear un proyecto se usa `gradle build`; una vez creado el directorio se tiene que crear un archivo `build.gradle` con la 
siguiente configuracion (ej, java)

```
	apply plugin: 'application'
	apply plugin: 'java'
	
	sourceCompatibility = 1.5	

	repositories {
        	jcenter() // or mavenCentral()
	}

	dependencies {
	}

	mainClassName = "main.Main"

	sourceSets {
        	main {
                	java {
                        	srcDir 'src'
                	}
        	}
	}

```			
luego de haber creado el archivo se vuelve a construir con `gradle build` y se ve que se creo un directorio `/build`
cada vez que se modifica el archivo hay que reconstruirlo.

Si se esta trabajando con eclipse se debe agregar el plugin ,y borrar todos los archivos de configuracion que no sean de 
gradle, luego construir el proyecto `gradle eclipse`.

Si en algun momento quiero usar una clase de otro paquete lo que se debe hacer es comprimir el paquete que la contiene, copiar 
y pegar en el sourceSets (en este caso es 'src') y utilizarlo como lo indique java con sus import package y demas.

Para ejecutar un programa dede la consola con gradle se usa el comando `gradle run`, para limpiar se usa `gradle clean`

