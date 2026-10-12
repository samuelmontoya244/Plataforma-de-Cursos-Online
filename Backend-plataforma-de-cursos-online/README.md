⚙️ Descripción del proyecto

Se desarrolló una API REST que permite manejar la lógica principal de una plataforma de cursos online. A través de esta API se pueden realizar operaciones como:

Registro e inicio de sesión de usuarios
Creación y gestión de cursos
Inscripción de usuarios en cursos
Consulta de información

La aplicación está diseñada siguiendo buenas prácticas de desarrollo backend, separando responsabilidades y permitiendo escalabilidad.

La API permite interactuar mediante endpoints REST. Algunos ejemplos:

POST /users → Crear usuario
POST /login → Autenticación
GET /courses → Obtener cursos
POST /courses → Crear curso

(Ajusta estos endpoints según tu código real)

🧪 Pruebas

Se pueden realizar pruebas directamente desde:

Swagger UI (/docs)
Postman
Thunder Client

🏫 Institución

Instituto Tecnológico Metropolitano (ITM)

📌 Notas adicionales
El servidor utiliza Uvicorn como ASGI server para ejecutar la aplicación FastAPI.
La arquitectura está pensada para facilitar futuras integraciones con frontend.
