# Reglas y Validaciones

## Inicio de sesión
- El usuario debe ingresar correo y contraseña.
- No se permite iniciar sesión con campos vacíos.
- Si las credenciales son incorrectas, se muestra un error.
- El sistema muestra opciones según el rol del usuario.

## Tours
- Todo tour debe tener los campos obligatorios completos.
- El precio no puede ser negativo.
- El cupo máximo debe ser mayor que 0.
- Los cupos disponibles no pueden ser mayores al cupo máximo.
- La hora de inicio debe ser menor que la hora de fin.

## Reservas
- Solo se puede reservar si hay cupos disponibles.
- No se puede reservar más personas de las permitidas por el tour.
- Al crear una reserva, disminuyen los cupos disponibles.
- Al cancelar una reserva, aumentan los cupos disponibles.
- El monto total se calcula con base en el precio del tour por la cantidad de personas.

## Notificaciones
- Al crear una reserva, se genera una notificación.
- Al cancelar una reserva, se genera una notificación.
- Las notificaciones pueden marcarse como leídas.

## Administración
- Solo el administrador puede crear, editar y eliminar tours.
- Solo el administrador puede acceder a la gestión general de reservas.