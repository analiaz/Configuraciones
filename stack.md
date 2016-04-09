#Stack

* Para la creacion de un proyecto en stack se ejecuta:
	`stack new <nombre-proyecto> <template>` 
* Los template son plantillas/esqueletos. 
		- `simple`: tiene una sola carpeta de codigo llamada `src/`
		- `new-template`: tiene una carpeta `app/` y una carpeta `src/`
* En .cabal se deben completar los campos vacios entrando en cada libreria que usea y estrayendo de ahi los datos (ej. 
licencia, version, etc)
* Para construir el proyecto se usa `stack build`

 
* Para mas informacion de stack y haskell en general [este link] (http://dev.stephendiehl.com/hask/).
