# Gestor de Gastos

## Descripción

Implementar un registro de gastos personales.
Los usuarios podrán registrar e ingresar mediante correo electrónico y contraseña.
Permitir clasificar los gastos personales en una o varias categorías.
Contar con un catálogo de categorías.
Al registrar un gasto, se deberá poder cargar una imagen del gasto.

- Instalación del proyecto con autenticación
	- Livewire
	- Vue

## Autorización

- Instalación con sistema de autenticación
- Las opciones para la gestión de los registros de gastos deberán ser previa autenticación

## UI

- Layout (opciones):
	- Utilizar layout incluido de laravel
	- Descargar e implementar template
	- Crear layout utilizando algún framework de css
- Mostrar enlaces para ingresar y salir del sistema
- Mostrar enlaces para operar el sistemas

## Catálogos (seeder)

- Categorías o clasificació
	- id, clasificacion / categoria 

## Registros de Gastos

- Listado, creación, detalle, edición y eliminación de gastos
	- El listado mostrará la fecha, descripción, monto y categoría o clasificación
	- Al ver detalle, mostrar imagen cargada
	- Al eliminar, eliminar imagen

Gastos:
- id
- user_id
- fecha
- descripcion
- forma_pago: efectivo, credito, debito
- monto
- imagen

### Relaciones

Un gasto puede pertenecer a muchas clasificaciones, una clasificación puede tener muchos gastos

### Validaciones

- fecha: requerida, fecha
- descripcion: requerido
- forma_pago: requerdio
- monto: requerido, numero, acepta 2 decimales, valores positivos
- imagen: 10 MB tamaño máximo

## Reglas (Gates o Policies)

- Cada usuario solo puede ver, editar o eliminar sus gastos

## Correo

- Envío de correo con los gastos del mes en que se genere el correo
	- Puede ser al hacer clic en algún botón que ejecute una ruta para que envíe el reporte de gastos

## Testing

Test de controlador y vistas para registro de gastos
