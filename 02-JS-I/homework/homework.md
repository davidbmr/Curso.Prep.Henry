• ¿Qué son las Variables?

Las variables son como cajitas las cuales nosotros le podemos elegir un nombre e insertar un valor.

Por ejemplo:
Tengo una cajita (variable) llamada "nombre", a esta cajita le puedo agregar un valor, "David"

Para crear una variable, es necesario empezar con la palabra "var":

var nombre;

Y para agregarle un valor, simplemente lo hacemos con el operador de igualdad "=":

nombre = "David";

Se puede también crear y agregar el valor en una misma línea de código:

var nombre = "David";

• ¿Qué son los Strings?

Los strings o también llamados cadenas de texto, es la forma en la cual nosotros escribimos un texto. Parar saber que es una cadena de texto, este debe de estar incluida en comillas dobles ("") o en comillas simples (''). Estos pueden ser incluidos en una variable.

Ejemplo:

var color = "Rojo"; // Rojo sería la cadena de texto.

La diferencia entre una variable y una cadena de texto, esta en las comillas ("", '').

• ¿Qué son las Funciones (argumentos, `return`)?

Las funciones también lo podemos imaginar como cajitas, pero en este caso estás cajitas contienen un proceso, es decir, pasos para lograr obtener un resultado.

Estas funciones le podemos colocar parametros/argumentos, las cuales son similares a las variables para cuando usemos la función, nosotros podemos elegir ciertos valores que queremos agregar. Estas tienen que estar dentro de ( ) y sí queremos colocar más parametros, estás deben de estar separadas por "," Ejm: (nombre, edad)

El contenido de una función debe de estar dentro de { }.

Para nosotros recibir el valor del resultado de estas funciones, es necesario colocarlos con la palabra reservada return.

Ejemplo de una función:

function saludo(nombre) {
return "Hola " + nombre;
}

• ¿Qué son las Declaraciones `if`?

Las declaraciones if son condicionales, como su mismo nombre lo dice if (si ...).
Lo usamos en gran medida cuando queremos validar cierta información, saber si es verdadero o falso.

Con el "if", también encontramos el "else", la cual se ejecuta siempre que la condición en el "if" sea falsa.

Ejemplo:

if (condición) { //Si la condición es verdadera, me arroja un string "verdadero"
return "verdadero"
} else { //Si la condición anterior es falsa, me arroja un string "falso"
falso "falso"
}

Podriamos decir que es:
Si pasa esto, resuelve de manera A,
Sino, resuelve de manera B.

• ¿Qué son los Valores booleanos (`true`, `false`)?

Los valores booleanos estan compuestos por 2 tipos. true y false (Verdaderos y falsos).

Esto se usa para indicar si una condición es verdadera o falsa.

Ejemplo:

( 1 === 1) // Esto dará true
( 1 === "1") // Esto dará false
( 1 === "Hola") // Esto dará false
