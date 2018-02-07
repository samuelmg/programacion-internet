# Requisitos a cumplir

Se espera un sistema web utilizando Laravel como framework de desarrollo.

## Base de datos

* Uso de migraciones para crear y modificar tablas.
* Implementar al menos un Seeder.
* Agregar datos de prueba en al menos una tabla.

## Autenticación, autorización y seguridad

* Realizar autenticación de usuarios mediante correo y contraseña.
* Validar toda información que se reciba a partir de una formulario.
* Implementar al menos dos middlewares.
* Implementar al menos en una ocasión Gates y Policies
* **Extra:** Passport / Socialite

## GUI

* Crear vistas utilizando blade
* Crear al menos un layout e implementarlo en vistas
	* Mostrar nombre, nombre de usuario o correo del usuario.
	* Mostrar opción para ingresar (login) o salir (logout) del sistema según corresponda.
	* Mostrar menú de navegación.
* Implementar Bootstrap
* **Importante:** Mostrar mensajes al usuario cuando:
	* Exista un error de validación al completar un formulario.
	* Se haya completado una tarea, sea con éxito, con errores o si require información adicional. (Ej. Al crear, eliminar o editar).
	* Existan listados vacíos.
* Cuando exista un error al validar un formulario o se esté editando información de un recurso existente, el formulario deberá mostrar la información capturada o a editar.
* Los enlaces o inclusión de recursos locales (css, js, etc) deberán generarse utilizando los helpers adecuados. (Ej. action, route, asset).

## Eloquent (Modelos, consultas)

* Tener al menos una relación de cada uno de los siguientes tipos y sus inversas:
	* "uno a muchos" (1:n)
	* "muchos a muchos" (n:n)
	* polimórfica o polimórfica muchos a muchos.
* Utilizar "Eager Loading" al consultar múltiples registros con n relaciones.
* Utilizar al menos en una consulta "Constraining Eager Load".
* Declarar "fillable".
* Almacenar información adicional en al menos una tabla pivote.
* Implementar "time stamps" en al menos un modelo.
* Implementar "Soft Delete" en al menos un modelo.
* Crear al menos un "accessor" y un "muttator" en al menos un modelo.

## Controladores

* Crear al menos un controlador tipo resource.
* **Extra:** Crear un controlador tipo resource anidado.
* Crear al menos un controlador con al menos un método personalizado.

## API

* Crear y consultar al menos un controlador con al menos un método que regrese un json.

## Archivos

Se deberá crear e implementar un cargador de archivos que permita:

* Cargar un archivo.
* Listar o mostrar el archivo cargado.
* Eliminar el archivo.
* **Extra:** Cargar múltiples archivos.

# Entregables



