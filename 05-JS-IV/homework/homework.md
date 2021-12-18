    * Objetos

En programación, los objetos son algo que contienen caracteristicas, para crear un objeto es necesario añadirlo a una variable e igualarlo a { }, dentro de estas llaves estarán sus caracteristicas.

Así se crearía un objeto:

let obj = {
caracteristicas
};

    * Propiedades

Las propiedades son las caracteristicas de los objetos, imaginemos que tenemos un objeto "persona", esta persona puede tener sus caracteristicas como "nombre", "apellido", "edad".

Se escribiría así

let persona = {
nombre: "David",
apellido: "Machuca",
edad: 24,
}

Como podremos observar, las propiedades al ser caracteristicas no llevan "", pero el valor de estas caracteristicas dependerá de su tipo, si queremos que sea un texto, si o si llevarán " ", pero si es un número, no será necesario.

    * Métodos

Los metodos son ciertas funciones que se encuentran dentro de un objeto, esto es super importante ya que como en la vida real, existen funciones a realizar.

Ejemplo, siguiendo con el objeto persona, a ello le podríamos agregar un método saludar.

Esto se haría de la siguiente manera:

let persona = {
nombre: "David",
apellido: "Machuca",
edad: 24,

saludar: function () {
return "Hola"
}

}

Cuando queramos invocar un método del objeto sería de la siguiente manera:

persona.saludar();

    * Bucle `for…in`

El bucle for in, se utiliza especificamente para iterar objetos, la cual se crea con los siguientes parametros, una variable que hace referencia a la llave y también el nombre del objeto a la cual queremos iterar.

let objeto = {
nombre: "Jae",
edad: 26,
}

for (let key in objeto) {
console.log(key);
console.log(objeto[key]);
}

Retornaria
// nombre
// Jae
// edad
// 26

    * Notación de puntos vs notación de corchetes

Empecemos con la notación de puntos, esto hace referencia a la manera de llamar una propiedad de un objeto en especifico, es decir, si sabemos que el objeto tiene una propiedad llamada nombre, podríamos saber su valor de la siguiente manera:

persona.nombre;
Esto me devolvería el valor del nombre.

Con la notación de corchetes se podría hacer lo mismo, si sabemos que un objeto tiene una propiedad, podríamos llamar al valor de esa propiedad de la siguiente manera:

persona["nombre"];

Esto es muy útil también cuando queramos hacer referencias a propiedades que no sabemos su existencia a ciencia cierta, es decir, que lo tengamos que pasar por una variable.

Para ello se llamaría así:

persona[variable];

Esto va a depender realmente que valor tiene la variable, si podemos observar, en este ultimo ejemplo, dentro de los [ ] le quitamos las "", esto hace referencia a que estamos esperando el valor de una variable. Si en caso la variable valiera "edad", terminaría de la siguiente manera

persona["edad"];
