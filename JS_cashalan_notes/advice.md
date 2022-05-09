## Notas
* Hay una serie de palabras de JS que no se pueden usar como variables (Ya que estan reservadas) un ejemplo `var var = x` ya la consola te devolvera error
* tipos  de datos en variables 
   * strings es una cadena de caracteres y estan entre comillas simles ('')
   * numeros todo los tipos de numeros
        * te en cuenta que si escribes numeros dentros de comillas seran strings no numeros
   *boolean son los valores true y false
   *null es nada (no cero,un caracter vacio, es nada!🙂)
   *undefined es cuando declaras la variable pero vacia (esta declarada sin nada adentro)
* JS soporta una +(suma) -(resta) *(multiplicacion) /(division) y =(asignacion (!important entender esto))
    * tambien soporta %(modulo) que devuelve el resto de una division, este operador matemático dividirá los dos números y devolverá el resto
    * si sumas strings va a concatenar
    * si divide strings va a castear los datos (cambiara el tipo de datos)
    * Nan (Not a Number) te lo devuelve cuando JS no sabe que hacer
* funciones son  agrupaciones de codigo que se guardaran y lo podras reutilizar varias veces si sintaxis es `function nombre_funcion(argumento){//codigo}` aunque hay otras formas de escribir funciones
    * lo que se repite lo pondremos como variables y esas varaibles las cambiaremos en los s mira asi
    ```js
    //codigo repetido
    console.log('Hola mi nombre es alan');
    console.log('tengo 17 años');
    console.log('Hola mi nombre es chritofer');
    console.log('tengo 2 años');
    console.log('Hola mi nombre es sary');
    console.log('tengo 16 años');
    console.log('Hola mi nombre es paola');
    console.log('tengo 37 años');
    // esto retornara
        Hola mi nombre es alan
        tengo 17 años
        Hola mi nombre es chritofer
        tengo 2 años
        Hola mi nombre es sary
        tengo 16 años
        Hola mi nombre es paola
        tengo 37 años
    undefined
    // ves como se repite el codigo y solo cambia ciertas partes esas partes que cambian les crearemos una variable asi
    console.log('Hola mi nombre es ' + nombre);
    console.log('tengo ' + edad + ' años');
    // ese codigo ira dentro de una funcion, y relacionaremos los argumentos con nuestras variables asi
    function whoami(nombre, edad)  {
        console.log('Hola mi nombre es ' + nombre);
        console.log('tengo ' + edad + ' años');
    }
    // para invocar la funcion haremos
    whoami('alan', 17);
    // esto retornara
        Hola mi nombre es alan
        tengo 17 años
    undefined
    ```
    * los argumentos van separados de comas(,)
    * si no invocas(llamar) a la funcion todo lo que este dentro de esta no servira, es decir si declaras una funcion dentro de una funcion,solo podras invocar esa variable invocando la funcion, al lugar donde esta la variable se le llama scope; la funcion si puede acceder al scope global es dacir que si no ecuentra esa variable dentro buscara fuera (aunque si declaras la variable adentro aunque este vacia recuerda que su valor default sera undefined no significa que no exista)
    * console.log es una funcion sirve para imprimir un argumento