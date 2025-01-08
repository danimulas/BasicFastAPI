# Proyecto Básico de FastAPI 🚀

Este proyecto utiliza FastAPI para crear una API sencilla con acceso a una base de datos. Ideal para aprender las bases de este framework.

## Características 🔗

- CRUD de preguntas y opciones.
- Conexión a bases de datos usando SQLAlchemy.
- Validación de datos con Pydantic.

## Instalación 🛠

1. **Clona el repositorio**:

   ```bash
   git clone https://github.com/usuario/proyecto-fastapi-basico.git
   cd proyecto-fastapi-basico
2. **Crea un entorno virtual:**
   ```bash
   python -m venv env
   source env/bin/activate
3. **Instala dependencias**:
   ```bash

   pip install fastapi uvicorn sqlalchemy pydantic
   Configura tu base de datos en database.py.
## Endpoints Principales 🌐
- **`GET /`**: Mensaje de bienvenida.
- **`POST /questions/`**: Crea una pregunta con opciones.
- **`GET /questions/{id}`**: Obtiene una pregunta.
- **`GET /choices/{id}`**: Obtiene las opciones de una pregunta.
**Ejecución** 🎉
Inicia el servidor:
   ```bash
   uvicorn main:app --reload
**Visita la documentación interactiva en:**
Swagger UI
Redoc
