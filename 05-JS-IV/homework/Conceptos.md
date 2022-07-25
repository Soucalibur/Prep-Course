Conceptos

Objetos: es una forma de almacenamiento de datos que tiene javaScript utilizado en todo lo referido, ya sean arrays, funciones,
    etc. Estos tienen una forma de notacion entre llaves {}. Dentro se colocar los pares "clave : valor"("clave": nombre de 
    asignacion; ":": separador entre clave y valor; "valor": el dato asignado que puede verse mediante su clave). Funciones
    similares tienen los arrays, ya que estos se agrupan en [], y al buscar un valor se lo busca mediante su índice (0,1,2,etc)
    por lo que sus índices serían sus claves, y sus valores lo que está puesto en el array.

Propiedades: características de un objeto. Este nombre hace referencia al par clave-valor (clave: nombre de la propiedad; 
    valor: significado (contenido) asignado, al que se le puede llamar con el nombre clave denominado)

Métodos: sinónimo de funciones pero dentro de los objetos.

Bucle for…in: sirven igual que los for anteriores estudiados, con la diferencia de que no es especifica una variable con su valor
    (ej: i=0), ni su condición de ruptura (ej: i<10), ni su adición o sustracción de valores (ej: i++). En este caso se utiliza
    cuando las claves de un objeto no son numeros, por lo que hacer un buble for de lamanera tradicional sería inutil. 
    Para usarlo se usa la notacion: for "variable" in "objeto"{//codigos}. En "variable" asignamos un nombre a los datos que 
    vaya a buscar en el objeto (por lo general toma las claves). "in" es "en" (o "dentro" en español) para saber donde se aplica
    el bucle. "objeto" es el nombre del objeto donde se iterará.

Notación de puntos vs notación de corchetes: ambas resuelven lo mismo, a diferencia de que la notacion a puntos es quizas un poco
    mas rápida pero no hace conversiones como los corchetes. Es decir, si yo asigno una variable (var x = "uno") y hago un objeto "i" que tenga dentro una clave-valor (uno = 1) si quiero sacar el valor 1 debo llamarlo: i.uno para obtener 1, ya que si hago: i.x me dará undefined. Los corchetes hacen esta conversión para buscar el valor asignado (i[x] me dará 1)
    
    Ej: var i = { uno:1, dos:2}
        var x = "uno"
        console.log(i.uno) "dará 1"
        console.log(i.x) "dará undefined"
        console.log(i["uno"]) "dará 1"
        console.log(i[x]) "dará 1" 
