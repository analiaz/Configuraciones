#Creacion de Stack
1)primero se ejecuta:
	`stack new <nombre-proyecto> <template>` 
- los template son plantillas/esqueletos). 
		1. simple: tiene una sola carpeta de codgo llamada `src/`
		2. new-template: tiene una carpeta `app/` y una carpeta `src/`
- una vez creado, en el archivo .hs se redacta el codigo y en el .cabal se 
agregan las dependencias, cada vez que se cambia algo se construye de 
nuevo con `stack build` 
- en .cabal se deben completar los campos vacios entrando en cada libreria que usea y estrayendo de ahi los datos ej licencia, 
version, etc
