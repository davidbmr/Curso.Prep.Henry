1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

- `for`

For es una de las maneras de crear un bucle de código, es necesario cuando necesitamos hacer muchas tareas repetidas.

La forma de crear un for es la siguiente:

for (let i = 0; i < 5; i++) {
console.log('Esta es la vuelta número: ' + i)
}

Con cada vuelta que de el bucle, "i" incrementará su valor en 1. "i" empezará desde el 0 y terminará cuando i sea menor a 5, es decir, solamente dará 5 vueltas.

Es muy común en la programación empezar desde el 0, ya que en temas como arreglos, las posiciones empiezan desde el 0.

- `&&`, `||`, `!`

A estos caracteres se les conocen como operadores lógicos. Estos nos ayudarán con nuestra lógica de nuestro código.

`&&` en JavaScript significa AND, se utiliza cuando creemos en la condicional una doble condición. La cual se debe de cumplir en ambos casos para recién devolver algo.

let numero = 5;
if ( numero < 0 && numero > 6) {
console.log('El número esta entre los valores 1 y 5');
} else {
console.log('El número está fuera de los valores 1 y 5');
}

`||` en JavaScript significa OR, es similar al anterior, solamente que en vez de cumplirse ambas condiciones, aquí solo es necesario cumplir una de las 2 condiciones.

let numero = 5;
if ( numero < 0 || numero > 0) {
console.log('El número no es 0');
} else {
console.log('El número si es 0');
}

`!` en JavaScript significa NOT, en pocas palabras, es la negación de una afirmación.

let bool = false;
if ( !bool === true) {
console.log('Es verdadero');
} else {
console.log('Es falso');
}
