# Entidades del Sistema

## Usuario
- id
- nombre
- correo
- contraseña
- rol
- fotoPerfil (opcional)

## Tour
- id
- nombre
- descripción
- categoría
- provincia
- ubicaciónTexto
- enlaceMapa
- precio
- duración
- fecha
- horaInicio
- horaFin
- cupoMáximo
- cuposDisponibles
- imagen
- estado

## Reserva
- id
- usuarioId
- tourId
- fechaReserva
- cantidadPersonas
- estado
- montoTotal

## Notificación
- id
- usuarioId
- título
- mensaje
- tipo
- fecha
- leída