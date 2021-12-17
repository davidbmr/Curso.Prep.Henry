1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

   - Arrays

Los arrays (En español, arreglos), son una estructura que contienen diferentes tipos de datos. Imaginemos que tenemos un tren, el tren esta compuesto por varios carritos y dentro de estos carritos entran ciertas personas o cosas. Lo mismo sucede en los arreglos.

Se podría decir que un array es el tren, y dentro contiene carritos "posiciones" las cuales le guardamos ciertos datos.

La estructura de un array empieza con [ ] y los datos se introducen dentro, las separaciones de los datos se va a dar con la ","

Ejemplo de un array:

let arr = [ 1, 2, 3, 4, 5];

El array (arr), contiene 5 elementos, las cuales son del número 1 al 5. Si hablamos de las posiciones de un arreglo es donde la mayoria de las personas nuevas tienden a confundir, ya que en la programación las posiciones empiezan desde el número 0.

Es decir, el valor de la posición "0" del array vale "1", El valor de la posición "1" del array vale "2", y así hasta llegar al valor de la posición "4" la cual vale "5". Derrepente con este ejemplo es algo confuso pero te pondré otro ejemplo.

Vamos a crear un array de frutas.

let frutas = ["manzana", "papaya", "pera"];

En este arreglo podemos ver que tenemos 3 elementos.

El valor de la posición "0", es "manzana", el valor de la posición "1" es "papaya", y el valor de la posición "2" es "pera".

Como podemos acceder a un valor en especifico del arreglo?, fácil, para ello es importante las posiciones.

Si yo quiero acceder al valor de la posición 0 de mi arreglo de frutas, tendría que llamarlo así:

frutas[0]; Esto me dará como resultado "manzana".

Sí yo quiero el valor de la posición 2 de mi arreglo frutas, sería la siguiente:

frutas[2]; La cual me dará como resultado "pera".

Sencillo.
