Conceptos

for: función que permite repetir secuencias de codigos de manera limitada, determinada por las mismas condiciones que uno mismo le
    introduce. Tiene 3 parámetros a estipular para que funcione. El primero es para crear una variable y asignarle un valor (por lo general es numérico). El segundo es para indicar la condicion de que, en caso de no cumplirse, el "for" se detiene. El tercero sirve como contador, ya que de esa forma el "for" puede detenerse, sino seria un bucle infinito.

Operadores lógicos

&& ("and"): sirve para hacer comparaciones y retornar valores booleanos (de verdadero o falso). Este operador devuelve "true"
    solamente cuando todos los elementos a comparar sean ciertos, caso contrario será "false".

|| ("or"): sirve para comparar valores y devolver "true" o "false". Será "true" en caso de que uno de los elementos comparados 
    sea verdadero, caso contrario será "false".
    
! ("not"): utilizado para comparaciones, las cuales devuelven "true" o "false" pero al revés. En este caso al dar indicaciones 
    de "not algunElemento" quiere decir que estamos buscando su valor booleano contrario (ya que el "not" funciona como negación)
    Un ejemplo sería comparar que 1 === 1, lo cual es cierto a menos que o se cambien los valores o se anteponga el signo "!",
    lo cual seria falso (!(1===1))