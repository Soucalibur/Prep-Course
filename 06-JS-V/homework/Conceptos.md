Conceptos

prototype: referente a primero, sirve para crear métodos que deban repetirse muchas veces en varios objetos, con la intención
    de ahorrar espacio en memoria y de ser tan repetitivos. Para utilizarlo primero se creauna función con algún nombre 
    (ej: nombreFuncionCreadora()) luego de darle los atributos podemos crear sus métodos: 
    nombreFuncionCreadora.prototype.nombreMetodo = function(){codigos}. Al crear una variable podemos acceder a este metodo 
    (siempre y cuando se haya enlazado con esta clase con "new") de la siguiente forma:
    nombreVariable.nombreMetodo()

Constructors (de Clases): son funciones que permiten crear objetos sin repetir muchos comandos. Para utilizarlo se llama a
    funtion NombreConstructorFuncion (con/sin parámetros){this.codigos=codigos;etc}. De esta manera podemos crear varios
    objetos que tengan las mismas propiedades sin tener que repetir el mismo codigo tantas veces, solventando tiempo y errores.