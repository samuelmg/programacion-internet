# Actividad extracurricular

## Descripción

Registro de eventos a los que asiste un alumno.
Existen dos tipos de usuarios: alumnos y administradores

## Requerimientos

### Generales

- Crear o modificar página de inicio para mostrar información básica del sistema (landing page).
- Enlaces para registrarse o iniciar sesión desde la página de inicio.
- El listado de eventos podrá ser consultado sin haber iniciado sesión.
    - Para inscribirse, se deberá iniciar sesión.

### Historias de usuario

- Como alumno deseo ver un listado de eventos que no han pasado para poder inscribirme.
- Como alumno quiero poder inscribirme a un evento para ganar créditos.
- Como alumno, al inscribirme, deseo recibir un correo que me notifique que estoy inscrito a un evento.
- Como alumno puedo ver el listado de eventos a los que estoy inscrito.
- Como alumno puedo cargar archivos (fotos o documentos) relacionados con el evento, como evidencia de mi participación en el evento.
- Como alumno puede eliminar archivos cargados.

## Reglas

- Solo los alumnos (no administradores) pueden "inscribirse" a un evento
- Un alumno solo puede cargar archivos a eventos que esté inscrito
- Un alumno solo puede eliminar archivos que sean suyos.
- Un alumno no se puede inscribir a un evento para el que ya esté inscrito

## Guía

- Crear eventos con fechas previas y futuras a la actual, mediante el uso de EventoFactory y DatabseSeeder y/o EventoSeeder
- Implementar método index de EventoController para listar los eventos próximos (>= al día actual).
	- Agregar enlace hacia detalle del evento (show)
- Crear tabla para almacenar la información de los archivos cargados
	- Deberá incluir referencias hacia user_id y evento_id
- Implementar método show de EventoController para mostrar el detalle de un evento:
	- Si el alumno no está inscrito, permitir inscribirse:
		- Agregar enlace o formulario que envíe la información para relacionar al alumno con el evento
	- Enviar correo al alumno al inscribirse.
	- Si el alumno está inscrito, permitirle cargar archivos.
	- Los archivos se listarán o mostrarán desde esta misma vista.
	- El alumno podrá eliminar archivos cargados desde esta vista
	- Solo se deberán mostrar archivos cargados por el alumno

## Notas

- Las reglas y permisos deberán ser desarrollados mediante gates y/o policies y se deberán aplicar tanto en el fronend (vistas) como en el backend (controladores).
