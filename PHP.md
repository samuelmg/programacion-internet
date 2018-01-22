# PHP

## Sintaxis Básica

`<?php //Código PHP ?>`

No se requieren declarar las variables, se crean al momento en que se asigna un valor.

Reglas para nombre de variables:

* Inician con signo de pesos $ seguido por el nombre de la variable.
* Iniciar con una letra o `_`.
* No puede iniciar con un número.
* Solo pude contener caracteres alfanuméricos y guión bajo (A-z, 0-9, and _ ).
* Sensible a mayúsculas minúsculas.

## Salida de variables

* `echo "Bla bla $variable";`
* `echo "Bla " . $variable . "bla";`
* `echo $x + $y;`


## Tipo de datos

* String
* Integer
* Float (floating point numbers - also called double)
* Boolean
* Array
* Object
* NULL
* Resource

### Arreglos

`$cars = array("Volvo", "BMW", "Toyota");`
`$cars[0] = "Volvo";
$cars[1] = "BMW";
$cars[2] = "Toyota";
`

* `count($arreglo)` Determina la longitud del arreglo.
* Arreglos Asociativos

Utiliza "nombres" para las llaves:
`$age = array("Peter"=>"35", "Ben"=>"37", "Joe"=>"43");`
`$age['Peter'] = "35";
$age['Ben'] = "37";
$age['Joe'] = "43";`
`$age = array("Peter"=>"35", "Ben"=>"37", "Joe"=>"43");
foreach($age as $x => $x_value) {
    echo "Key=" . $x . ", Value=" . $x_value;
    echo "<br>";
}`


## If...Else...Elseif

`if (condición) {código a ejecutar}`
`if (condición) {código si condición es verdadera} else {código si condición es falsa}`
`if (condición) {código si condición es verdadera} elseif (condición2) {código si condición2 es verdadera}`

## Switch

`<?php
switch (n) {
    case label1:
        code to be executed if n=label1;
        break;
    case label2:
        code to be executed if n=label2;
        break;
    case label3:
        code to be executed if n=label3;
        break;
    ...
    default:
        code to be executed if n is different from all labels;
}
?>`

## Ciclos

* while: Ejecuta bloque mientras la condición sea verdadera.

`<?php
$x = 1;
while($x <= 5) {
    echo "The number is: $x <br>";
    $x++;
}
?>`

* do...while: Ejecuta una vez bloque, y después repite la ejecución mientras la condición sea verdadera.

`<?php
$x = 1;
do {
    echo "The number is: $x <br>";
    $x++;
} while ($x <= 5);
?>`

* for: Ejecuta bloque un cierto número de veces.

`<?php
for ($x = 0; $x <= 10; $x++) {
    echo "The number is: $x <br>";
} 
?>`

* foreach: Ejecuta bloque para cada elemento en un arreglo.

`<?php 
$colors = array("red", "green", "blue", "yellow"); 
foreach ($colors as $value) {
    echo "$value <br>";
}
?>`


## Variables Superglobales

Son variables predefinidas de PHP siempre accesibles
* $GLOBALS
* $_SERVER

`<?php 
echo $_SERVER['PHP_SELF'];
echo "<br>";
echo $_SERVER['SERVER_NAME'];
echo "<br>";
echo $_SERVER['HTTP_HOST'];
echo "<br>";
echo $_SERVER['HTTP_REFERER'];
echo "<br>";
echo $_SERVER['HTTP_USER_AGENT'];
echo "<br>";
echo $_SERVER['SCRIPT_NAME'];
?>`

* $_REQUEST
* $_POST
* $_GET
* $_FILES
* $_ENV
* $_COOKIE
* $_SESSION

## GET vs. POST

* $_GET es un arreglo de variables pasadas al script mediante parámetros en la URL.
* $_POST es un arreglo de variables pasadas al script actual mediante el método HTTP POST.


## MySQL

* MySQLi extension (the "i" stands for improved)
* PDO (PHP Data Objects)

