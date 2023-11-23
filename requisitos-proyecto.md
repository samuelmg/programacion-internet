# Proyecto Final

El objetivo es que experimenten desarrollar un sistema pensando como un *full stack developer*, es decir que diseñen tanto el *backend* (base de datos, relaciones, validaciones), así como el *frontend* (vistas, html, js, css) y con ello lograr un sistema que brinde una buena experiencia de uso al usuario final.

## Almacenamiento de la información (Database) - (100)

- Esquema de la base de datos o sistema de almacenamiento (Migrations). - 50
- Generación de datos de prueba o catálogos (Seeders & Factories). - 30
- Asignación de Foreign Key Constraints - 20

## Autenticación y autorización - (100)

- Registro y autenticación de usuarios (login/logout, Sessions, Middleware Auth). - 40
- Restringir, permitir o modificar el comportamiento, opciones o acciones en función del tipo de usuario o condiciones (Gates, Policies, Middleware). - 60

## Validación - (100)

- Todo formulario deberá ser validado en el lado del servidor. - 70
- Agregar validaciones en el cliente mediante html5 o js. - 30

## UI/UX - (130)

- Implementar diseño responsivo. Se sugiere utilizar un framework de CSS o un template basado en framework de CSS. - 50
- Se sugiere reutilizar elementos comunes (layout, partial views, components). - 20
- Mostrar login/logout. - 10
- Mostrar errores de validación de formularios. - 20
- Mostrar mensajes de éxito al crear, editar o eliminar registros. - 10 (opcional/extra)
- Navegación dentro de la aplicación (navbar, menu, breadcrumb). - 20

## ORM: Object-Relational mapping (Eloquent) (100)

- Implementar clases que describan el sistema de almacenamiento (tablas y sus relaciones) (Modelos). - 50
- Utilizar estas clases y métodos para consulta y almacenamiento de la información. - 50

## Operación CRUD (100)

- Implementar al menos un CRUD (Resource Controller). - 100

## Relaciones (100)

- La información almacenada deberá estar relacionada:
	+ Uno a muchos (1:m). - 50
	+ Muchos a muchos (m:n). - 50

## Consulta, creación y eliminación de información (50)

- Resolver problema de N + 1 consultas (Eager loading) - 20
- Implementar borrado lógico (Soft Deletes). - 20
- Modificar información al consultar o guardar (Accessors, Muttators). - 10

## API (20)

- Crear ruta que realice una consulta y cuya respuesta sea un JSON. - 20 (opcional/extra)

## Archivos (100)

- Carga de archivos, uno o muchos a la vez. - 50
- Mostrar archivo o listado de archivos. - 30
- Eliminar o reemplazar archivos. - 20 (opcional/extra)

## Correo electrónico (100)

- Implementar el envío de correo electrónico en al menos una de las siguientes modalidades: - 100
  - Verificación de correo al crear cuenta de usuario.
  - Envío de correo electrónico personalizado.

## Extras

Implementar cualquiera de los siguiente temas les brindará puntos adicionales, los temas se encuentran en lo que considero en orden de dificultad, del más sencillo al más complejo, no por su dificultad sino porque hay que leer más documentación específica.

- Crear una relación con más de un modelo (Polimórfica). - 20
- Relación muchos a muchos con información particular a la relación (información adicional en tabla pivote). - 20
- Generar documento pdf, excel, word, etc. - 20
- Programación de tareas recurrentes (Task Scheduling). - 30
- Creación de colas de tareas (Jobs). - 30
- Autenticación mediante credenciales de terceros (google, twitter, facebook, github). - 50
- Implementar sistema de pago. - 50
