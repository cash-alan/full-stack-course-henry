```js
// data
var /*variable_nombre*/ = /*variable_valor*/; : sirve para declarar variables
const /*nombre_constante*/ = /*constante_valor*/; : sirve para declarar constantes
/*dato*/ /*operador*/ /*dato*/ : sirve para hacer operaciones
// operadores
/*dato*/ + /*dato*/ : suma o concatena
/*dato*/ - /*dato*/ : resta 
/*dato*/ * /*dato*/ : multiplica
/*dato*/ / /*divide*/ : divide
/*dato*/ % /*divide*/ : divide y devuelve el residuo
/*dato*/  /*divide*/ : compara si el primero es menor que el segundo
/*dato*/  /*divide*/ : compara si el primero es mayor que el segundo
/*dato*/ == /*divide*/ : compara si el primero es igual que el segundo
/*dato*/ === /*divide*/ : compara si el primero es igual que el segundo en todo
/*dato*/++ : sumara uno al dato es igual a (/*dato*/ + 1;)
// function 
function  /*nombre_funcion(/*argumentos) {/*/*codigo*/ : sirve para crear funciones
const /*nombre_funcion = function () {/*/*codigo*/; : sirve para crear funciones dentro de variables (fijate que se nombra la variable no la funcion)
(/*parametros*/) = {/*codigo*/;} : es una forma resumida de crear funciones anonimas(sin nombre),si la funcion solo tiene una linea de codigo y/o un parametro puedes omitir las llaves y/o los parentesis (quedando algo asi /*parametro*/=/*codigo*/;)
return /**/; : sirve para retornar valores
//hay funciones ya predeterminadas llamadas metodos como
console.log('argumento') : sirve para imprimir cualquier dato que le indiques por argumento
alert('argumento') : muestra una ventana de alerta con el argumento que le des
prompt('argumento') : muestra una ventana de alerta con el argumento que le des pidiendo datos al usuario
Math./*method*/() : son algunas operaciones matematicas
Math.min() : Para encontrar el valor mínimo presente
Math.max() : Para encontrar el valor máximo presente
// condicionals
if (condicion) {} : sirve para crear el condicional
else {} : se escribe al final y se ejecuta cuando todo lo demas es falso (va siempre al final)
else if (condicion) {} : es como sino con condicion como un entonces (va siempre despues del if)
switch(n){case n_valor:/*codigo*/case n_valor:/*codigo*/ default(opcional)} : sirve para dar varias condiciones
return /*codigo*/; : sirve para retornar valores y termina de ejecutar el codigo cuando se enuncie
break; : obliga a terminar el codigo
// loops
for (/*variable_contador*/;/*condicion_true*/;/*accion/acumulacion*/) {/*codigo*/} : sirve para crear iteraciones
for (/*variable_elemento*/ of /*objeto*/){/*codigo*/} : sirve para iterar en objetos(arrays,strings,maps,...), equivalentes a for (let i=0;iarray.length;i++){console.log(array[i]);} ===  for (let e  of array){console.log(e);}, como ejemplo 
while(/*condicion*/) {} : sirve para crear bucles sin saber que cantidad de veces se repite
do{/*codigo*/}while(/*condicion*/);  : sirve para crear bucles sin saber que cantidad de veces se repite pero el do siempre lo va a ejecutar una vez
// arrays
[/*datos*/] : es un array
array.push() : envia datos al final del array
array.pop() : elimina y trae el ultimo dato del array
array.unshift() : colocará un nuevo elemento en la primera posición de la matriz 
array.shift() : elimina y trae el primer elemento de la matriz
array.lenght() : nos dice cuantos valores tiene un array
array.map() : toma cada elemento del arreglo y lo usa en una función para devolver un nuevo valor en la misma posición de un nuevo arreglo.
array.filter(): para encontrar los elementos dentro de un arreglo que cumplan con cierta condición
array.indexOf() : devuelve el primer índice encontrado de un elemento específico
array.includes() : determina si un arreglo incluye un valor específico y devuelve verdadero o falso según corresponda
array.find() : para encontrar el primer elemento que cumple cierta condición
```