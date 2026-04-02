# Endpoints del Sistema

## Auth
- POST /auth/login
- POST /auth/register
- POST /auth/logout
- GET /users/me

## Tours
- GET /tours?page=1&limit=10&search=&categoria=&provincia=&fecha=
- GET /tours/{id}
- POST /tours
- PUT /tours/{id}
- DELETE /tours/{id}

## Reservas
- GET /reservations?userId=
- GET /reservations/{id}
- POST /reservations
- PATCH /reservations/{id}/cancel
- GET /admin/reservations?page=1&limit=10&estado=

## Notificaciones
- GET /notifications?userId=&page=1&limit=10
- PATCH /notifications/{id}/read
- POST /notifications

## Admin
- GET /admin/dashboard