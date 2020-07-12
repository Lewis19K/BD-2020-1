Luis Alberto Corrales Palma
Rol: 201804577-2




El programa al iniciarse presenta un menu que presenta las opciones de forma numerica,
donde cada opcion es representada con un numero el cual se ingresa por consola.
El menu consta de 8 consultas, un menu secundario donde se encuentran las acciones del CRUD
y la opcion de cerrar el programa.




Aclaraciones con respecto al funcionamiento de las funciones:

Ingresar pokemon:
	Cuando se ingresa un pokemon a la tabla Sansanito_Pokemon y con respecto a la capacidad de esta
	tabla ya se ha alcanzado el limite se procede a verificar las prioridades para ver si entra el
	pokemon que se desea ingresar a la tabla.

	-Si el pokemon que se ingresa no es legendario, se compara con el pokemon no legendario con
	menor prioridad para ver si entra y sale dicho pokemon con menor prioridad.

	-Si el pokemon es legendario se compara analogamente, pero con respecto a pokemon legendarios,
	es decir, que si no hay ningun legendario en la tabla Sansanito_Pokemon, no podra ser ingresado
	ningun legendario mientras la capacidad este llena.