#Stack

1. Para la creacion de un proyecto en stack se ejecuta:
	`stack new <nombre-proyecto> <template>` 
2. Los template son plantillas/esqueletos. 
	* `simple`: tiene una sola carpeta de codigo llamada `src/`
	* `new-template`: tiene una carpeta `app/` y una carpeta `src/`
3. En .cabal se deben completar los campos vacios entrando en cada libreria que usea y estrayendo de ahi los datos (ej. 
licencia, version, etc)
4. Para construir el proyecto se usa `stack build`

 
- Para mas informacion de stack y haskell en general ["este link"] (http://dev.stephendiehl.com/hask/).
