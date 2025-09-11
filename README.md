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

🔒 Requerimientos no funcionales

Escalabilidad: los microservicios deben poder desplegarse y escalarse de manera independiente.

Seguridad: autenticación y autorización con JWT u OAuth2.

Disponibilidad: sistema tolerante a fallos con posibilidad de orquestación (Docker/Kubernetes).

Mantenibilidad: código organizado, modular y con documentación clara.

Portabilidad: cada microservicio debe correr en contenedores para fácil despliegue.

Monitoreo y logs: integración futura con herramientas de observabilidad (Prometheus, Grafana, ELK).

📦 Tecnologías a usar (mínimas)

Backend: Python (FastAPI o Django Rest Framework).

Base de datos: MySQL/PostgreSQL (según microservicio).

Mensajería/colas (futuro): RabbitMQ o Kafka.

Contenedores: Docker.

Gestión de repositorios: Git + GitHub.

📦 Tecnologías a usar (mínimas)

Backend: Python (FastAPI o Django Rest Framework).

Base de datos: MySQL/PostgreSQL (según microservicio).

Mensajería/colas (futuro): RabbitMQ o Kafka.

Contenedores: Docker.

Gestión de repositorios: Git + GitHub.


Imagen referencial 
<img width="1852" height="919" alt="image" src="https://github.com/user-attachments/assets/422438d8-ee87-4678-9e76-da402ac3ab7c" />

