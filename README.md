📝 Descripción breve

Este proyecto tiene como objetivo construir una plataforma de aprendizaje en línea basada en microservicios, que permita la gestión de cursos, usuarios, inscripciones y otros módulos relacionados a la educación digital.
Se busca escalabilidad, modularidad y facilidad de despliegue en entornos distribuidos.
Requerimientos funcionales

Gestión de cursos

Crear, editar, eliminar y listar cursos.

Asignar categorías, niveles y etiquetas a cada curso.

Gestión de usuarios

Registro y autenticación de estudiantes y docentes.

Perfil de usuario con historial de cursos.

Inscripciones y matrículas

Los estudiantes pueden inscribirse en cursos disponibles.

Validación de cupos y disponibilidad.

Microservicios independientes

Servicio de usuarios.

Servicio de cursos.

Servicio de inscripciones.

Servicio de notificaciones (ej: recordatorios por email).

API RESTful

Endpoints documentados para cada servicio.

Comunicación entre microservicios vía HTTP/JSON (o gRPC más adelante).

Persistencia de datos

Cada microservicio maneja su propia base de datos.
