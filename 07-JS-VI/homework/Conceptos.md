Conceptos

Funciones Callback: son llamados de funciones dentro de funciones (es decir, realizo una funcion y dentro,como argumento, 
    le paso una funcion).
    
    Ej: function sumar (x,y){
        return x+y;
    }
    function resultadoDescriptivo(x,y,cb){
        return "El resultado de la operacion entre "+ x +" + " +y+" es: " + cb(x,y)
    }

    console.log(sumar(2,3))   // 5
    console.log(resultadoDescriptivo(3,4,sumar))   // "El resultado de la operacion entre 3 + 4 es: 7"