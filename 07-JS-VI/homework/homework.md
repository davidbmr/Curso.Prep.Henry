- Funciones Callback

En javascript cuando pasamos como argumento de una función otra función, esto se demonima como función de callback. Podríamos decir que una función callback es aquella que se encuentra dentro de otra función. La forma común de saber que estamos pasando un callback es colocando cb.

Ejemplo:

let sumar = function (a, b) {
return a + b;
}

let resultado = function(n1, n2, cb) {
return cb(n1, n2);
}

resultado(1,2, sumar);

dará como resultado: 3
