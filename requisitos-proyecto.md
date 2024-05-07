# Proyecto Final

El objetivo es que experimenten desarrollar un sistema pensando como un *full stack developer*, es decir que diseñen tanto el *backend* (base de datos, relaciones, validaciones), así como el *frontend* (vistas, html, js, css) y con ello lograr un sistema que brinde una buena experiencia de uso al usuario final.

## Almacenamiento de la información (Database) - (100)

- Esquema de la base de datos o sistema de almacenamiento (Migrations). - 50
- Generación de datos de prueba o catálogos (Seeders & Factories). - 30
- Asignación de Foreign Key Constraints - 20

## Autenticación y autorización - (100)

- Registro o creación de usuarios - 20
- Requerir autenticación de usuarios (Middleware auth). - 20
- Restringir, permitir o modificar el comportamiento, opciones o acciones en función del tipo de usuario o condiciones; tanto en vistas como en backend (controladores) (Gates, Policies, Middleware). - 60

## Validación - (100)

- Todo formulario deberá ser validado en el lado del servidor. - 70
- Agregar validaciones en el cliente mediante html5 o js. - 30

## UI/UX - (150)

- Implementar CSS responsiva. Se sugiere utilizar un framework de CSS o un template basado en framework de CSS. - 50
- Utilizar al menos un layout. - 30
- Reutilizar elementos comunes (partial views, components). - 20
- Mostrar login/logout. - 10
- Mostrar errores de validación de formularios. - 20
- Navegación dentro de la aplicación (navbar, menu). - 20

## ORM: Object-Relational mapping (Eloquent) (100)

- Implementar clases que describan el sistema de almacenamiento (tablas y sus relaciones) (Modelos). - 50
- Utilizar estas clases y métodos para consulta y almacenamiento de la información. - 50

## Operación CRUD (70)

- Implementar al menos un CRUD (Resource Controller). - 70
  + Listado (index)
  + Formulario de creación (create)
  + Creación (store)
  + Detalle (show)
  + Formulario de edición (edit)
  + Actualización (update)
  + Borrar (destroy)

## Relaciones (60)

- La información almacenada deberá estar relacionada, tanto a nivel de base de datos como en modelos:
	+ Uno a muchos (1:m). - 30
	+ Muchos a muchos (m:n). - 30

## Consulta, creación y eliminación de información (20)

- Si se utilizan consultas de SQL crudas o QueryBuilder - (menos 100 puntos si no se tiene una justificación técnica)
- Resolver problema de N + 1 consultas (Eager loading) - (menos 30 puntos si se requiere pero no se implementa solución)
- Implementar borrado lógico (Soft Deletes). - 20

## Archivos (100)

- Carga de archivos, uno o muchos a la vez. - 50
- (Mostrar archivo) o (listado de archivos y descarga). - 50
- Eliminar o reemplazar archivos. - 20 (opcional/extra)

## Correo electrónico (100)

- Verificación de correo al crear cuenta de usuario. - 10 (opcional/extra)
- Envío de correo electrónico personalizado. - 100

## Testing (100)

- Siendo usuario X, al consultar ruta Y, aseguro código 200 y se muestra un texto determinado. - 25
- Siendo usuario X, al enviar petición POST, aseguro creación de registro en DB y redireccionamiento. - 25
- Siendo usuario X, al enviar petición POST con información incorrecta o faltante, asegurar error en validación. - 25
- Siendu usaurio X, al enviar petición DELETE, aseguro eliminación de registro en DB y redireccionamiento. - 25

## Extras

Implementar cualquiera de los siguiente temas les brindará puntos adicionales, los temas se encuentran en lo que considero en orden de dificultad, del más sencillo al más complejo, no por su dificultad sino porque hay que leer más documentación específica.

- Crear una relación con más de un modelo (Polimórfica). - 20
- Relación muchos a muchos con información particular a la relación (información adicional en tabla pivote). - 20
- Generar documento pdf, excel, word, etc. - 20
- Programación de tareas recurrentes (Task Scheduling). - 30
- Creación de colas de tareas (Jobs). - 30
- Autenticación mediante credenciales de terceros (google, twitter, facebook, github). - 50
- Implementar sistema de pago. - 50
