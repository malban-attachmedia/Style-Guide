# Attachmedia Analytics Style Guide()
Lamentablemente Google Tag Manager (GTM) no permite usar ECMAScript 6 (ES6), por lo que esta guía está pensada para ES5.
## 1. Variables
1.1 Usar `var` cuando se desea declarar una variable. GTM no permite usar let y const.
```
// mal
let a=1;
const  b=2;

//bien
var c=3;
```
1.2 No dejar espacio entre el nombre de la variable, el operador y el contenido de la variable. En grandes cantidades de codigo, GTM puede generar errores al intentar compilar los espacios.
```
// mal 
var foo = 'mama';

// bien
var foo='papa';
```
## 2. Objetos
2.1 Declarar los objetos de la siguiente forma
```
//mal
var myObject=new Object();

//bien
var myObj={};
```
