# Programa

## Presentación

* Presentación
* Forma de Evaluación general
* Evaluación de tareas y ejercicios

## Introducción HTML / PHP

* HTML
  * Tags: doctype, html, head, title, body, h1, p, a, br, img, hr, ol, ul, li
* PHP
  * Variables
  * Arreglos
  * Métodos: for, foreach

### Ejercicio 1 Agenda Telefónica
  
  * Todas las páginas que muestren información deben contener los elementos doctype, html, head, body, título y subtítulo
  * Deberá tener un separador horizontal entre el título y el contenido de la página.
  * Utilizar CSS.

#### Ejercicio 1.0
  
   * Crear index.php
   * Crear lista con enlaces (menú): Inicio y Contactos
   * Agregar estilo

#### Ejercicio 1.1 Uso de Arreglos

* Crear página (indexContactos.php)
* Crear arreglo con nombre y teléfono de 10 personas.
  1. Crear arreglo `$arrInfo = array();`
  2. Asignar de forma manual 2 registros `$arrInfo[] = ['nombre' => '', 'tel' => '1234'];`
  3. Remplazar forma manual por un ciclo for `for($i = 0; $ < 6; $i++) {$arrInfo[] = ['nombre' => 'Persona ' . $i, 'tel' => $i * 11111111];}`
* Mostrar nombres y teléfonos del arreglo utilizando `foreach()` dentro de una tabla a dos columnas.

#### Ejercicio 1.2 Formularios

* Crear nueva página (formContacto.php)
* Agregar enlace (Nuevo) en indexContactos.php hacia formContacto.php
* Crear formulario para capturar nombre y número
* Utilizar label para cada campo

1. Enviar información a sí misma utilizando método GET
2. Utilizar `if()` para determinar si se recibe la información; realizar pruebas utilizando `isset()`, `is_null()`
2. Enviar información a sí misma utilizando método POST

#### Ejercicio 1.3 Agenda (Base de Datos)

* Crear base de datos (agenda) y tabla (personas) para almacenar nombre y número.
* Crear conexión hacia la base de datos.

1. Agregar en formAgenda.php SQL para insertar información recibida (Consultar en DB si se insertó el registro)
2. Utilizar F5 una vez que se envió el formulario para demostrar la reinserción de informaicón

* Crear storeAgenda.php y mover código que inserta a DB
* Agregar redireccionamiento (después de la inserción) hacia indexAgenda.php
* Agregar conexión a DB en indexAgenda.php
* Consultar DB para mostrar listado.

1. Demostrar inyección de SQL.
2. Proteger inserción de SQL.

## Actualización PHP 7.1 / MySQL 5.7

1. Crear nuevo contenedor Laravel 5.* en servidor Ubuntu
2. Actualizar servidor e instalación de Laravel siguiendo la guía: [Install Laravel 5.5 at Codeanywhere with PHP 7.1 and MySQL 5.7](https://wpkb.org/install-laravel-5-5-at-codeanywhere-with-php-7-1-and-mysql-5-7/).


