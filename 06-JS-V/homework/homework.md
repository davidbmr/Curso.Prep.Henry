- `prototype`

El prototipe es un espacio en memoria donde se almacenan los métodos en general de objeto, arreglo, etc. Esto se utiliza mucho cuando empezamos con la programación orientadas a objetos.

En la programación orientadas a objetos (POO), vamos a estar en la necesidad de crear muchos objetos, para ello se necesitará crear plantillas (funciones constructoras o clases), estas plantillas nos van a permitir crear objetos con caracteristicas definidas, solamente cambiariamos sus valores.

Todos sabemos que los objetos tienen ciertos métodos (funciones), que son para poder realizar una acción. Si nosotros agregamos el metodo directamente a cada objeto, esto a largo plazo ocuparia mucho espacio en memoria, lo que al final se traduciría en gasto de equipo y código lento.

Lo mejor es agregar los metodos en el prototipo de una plantilla, esto permitira compartir el mismo método a todos los objetos que se creen en base a esa plantilla. Así esto quedaría guardado en el prototipo y ahorrariamos capacidad en memoria.

La sintaxis para crear una función constructora:

function Persona(nombre, apellido, edad) {
this.nombre = nombre;
this.apellido = apellido;
this.edad = edad;
}

La palabra reservada "this" hace referencia al objeto que se va a crear.
Sí queremos usar esta plantilla y crear un objeto, sería de la siguiente manera:

const david = new Persona("David", "Machuca", 24);

Ello me crearía un objeto con las propiedades nombre, apellido y edad.

Sí queremos agregarle un método a su prototipo, sería de la siguiente manera:

Persona.prototype.saludar = function () {
return "Hola"
}

El objeto david hereda el método de su prototipo y también lo podría usar, como:

david.saludar();

- _Constructors_ (de Clases)

Los constructores de clases se crearon a partir del ECMAScript 6, en el año 2015, así dar facilidad de escribir un código más legible. Estas cumplen el mismo proposito que las anteriores (funciones constructoras) crear plantillas para objetos.

Antes, primero se tenia que crear la funcion constructora y después agregar metodos al prototypo y esto hacia que el código se pueda ver algo confuso.

Para ello, se crearon las clases, la cuales engloba desde la construcción del objeto hasta los prototipos dentro de la palabra reservada "class"

Ejemplo:

class Perro {
constructor(nombre, raza, color) {
this.nombre = nombre;
this.raza = raza;
this.color = color;
}

ladrar() {
return "guau"
}
}

Como podremos observar, los métodos creados fuera del constructor, se añaden al prototipo de la clase Perro, por ende todos los objetos creado en base a esta plantilla, heredarán el método ladrar.
