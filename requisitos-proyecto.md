# Proyecto Final

El objetivo es que experimenten desarrollar un sistema pensando como un *full stack developer*, es decir que diseñen tanto el *backend* (base de datos, relaciones, validaciones), así como el *frontend* (vistas, html, js, css) y con ello lograr un sistema que brinde una buena experiencia de uso al usuario final.

## Almacenamiento de la información (Database)

- Esquema de la base de datos o sistema de almacenamiento (Migrations).
- Generación de datos de prueba o catálogos (Seeders & Factories).
- Conservar registo de creación y edición de registros (Time Stamps).

## Autenticación y autorización

- Registro y autenticación de usuarios (login/logout, Sessions).
- Restringir, permitir o modificar el comportamiento, opciones o acciones en función del tipo de usuario o condiciones (Gates, Policies, Middleware).

## Validación

- Todo formulario deberá ser validado en el lado del servidor.
- Agregar validaciones en el cliente mediante html5 o js.

## UI/UX

- Implementar diseño responsivo. Se sugiere utilizar un framework de CSS.
- Se sugiere reutilizar elementos comunes (layout, partial views).
- Mostrar login/logout.
- Mostrar errores de validación de formularios.
- Mostrar mensajes de éxito al crear, editar o eliminar registros.
- Navegación dentro de la aplicación (navbar, menu, breadcrumb).

## ORM: Object-Relational mapping (Eloquent)

- Implementar clases que describan el sistema de almacenamiento (tablas y sus relaciones) (Modelos).
- Utilizar estas clases y métodos para consulta y almacenamiento de la información.

## MVC

- Implementar al menos un CRUD (Resource Controller).

## Relaciones

- La información almacenada deberá estar relacionada:
	+ Uno a muchos (1:m).
	+ Muchos a muchos (m:n).

## Consulta, creación y eliminación de información

- Consulta utilizando carga anticipada de información relacionada (Eager loading). //Solo en Laravel
- Implementar borrado lógico (Soft Deletes).
- Modificar información al consultar o guardar (Accessors, Muttators).

## API

- Crear ruta que realice una consulta y cuya respuesta sea un json

## Archivos

- Carga de archivos, uno o muchos a la vez.
- Mostrar archivo o listado de archivos.
- Eliminar o reemplazar archivos.

## Correo electrónico

Implementar el envío de correo electrónico en al menos una de las siguientes modalidades:

- Verificación de correo al crear cuenta de usuario.
- Envío de correo electrónico personalizado.

## Extras

Implementar cualquiera de los siguiente temas les brindará puntos adicionales, los temas se encuentran en lo que considero en orden de dificultad, del más sencillo al más complejo, no por su dificultad sino porque hay que leer más documentación específica.

- Crear una relación con más de un modelo (Polimórfica).
- Relación muchos a muchos con información particular a la relación (información adicional en tabla pivote).
- Generar documento pdf, excel, word, etc.
- Programación de tareas recurrentes (Task Scheduling).
- Creación de colas de tareas (Jobs).
- Autenticación mediante credenciales de terceros (google, twitter, facebook, github).
- Implementar sistema de pago.
