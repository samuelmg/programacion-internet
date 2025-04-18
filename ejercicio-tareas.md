# Tareas en equipo

## Descripción

Creación de tareas para realizar en equipo.

## Requerimientos

### Generales

- Crear o modificar página de inicio para mostrar información básica del sistema (landing page).
- Enlaces para registrarse o iniciar sesión desde la página de inicio.

### Historias de usuario

- Como alumno deseo crear tareas para poder invitar a mi equipo.
- Como alumno quiero poder invitar a otros usuarios a una de mis tareas para realizarlas en equipo.
- Como alumno invitado, debo recibir un correo informando que fui invitado a una tarea.
- Como alumno puedo eliminar mis tareas

## Reglas

- Un alumno solo puede invitar a usuarios a sus propias tareas
- El alumno no puede ver o invitar a tareas de otros alumnos

## Guía

- Crear tareas mediante TareaFactory y DatabaseSeeder y/o TareaSeeder
- Implementar index de TareaController para listar las tareas del usuario o tareas a las que se les ha invitado.
	- Agregar enlace hacia detalle de tarea (show)
- Crear tabla para almacenar la información de los archivos cargados
	- Deberá incluir referencias hacia user_id y tarea_id
- Implementar show de TareaController (detalle de la tarea)
	- Crear formulario para listar y seleccionar usuarios para invitarlos a la tarea
	- Al invitar a un usuario, enviar correo para notificarle
	- Los usuarios invitados o creador de la tarea deben:
		- Cargar archivos
		- Listar archivos
		- Eliminar archivos

## Notas

- Las reglas y permisos deberán ser desarrollados mediante gates y/o policies y se deberán aplicar tanto en el fronend (vistas) como en el backend (controladores).
