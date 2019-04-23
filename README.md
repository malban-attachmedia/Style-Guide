# Attachmedia Analytics Style Guide()
Lamentablemente Google Tag Manager (GTM) no permite usar ECMAScript 6 (ES6), por lo que esta guía está pensada para ES5.
## 1. IDE 
1.1 El IDE a usar en 
## 2. Variables
2.1 Usar `var` cuando se desea declarar una variable. GTM no permite usar let y const.
```
// mal
let a=1;
const  b=2;

//bien
var c=3;
```
2.2 No dejar espacio entre el nombre de la variable, el operador y el contenido de la variable. En grandes cantidades de codigo, GTM puede generar errores al intentar compilar los espacios.
```
// mal 
var foo = 'mama';

// bien
var foo='papa';
```
## 3. Objetos
3.1 Declarar los objetos de la siguiente forma
```
//mal
var myObject=new Object();

//bien
var myObj={};
```
