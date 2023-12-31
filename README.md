# API de Reseñas de Películas

Esta es una API de reseñas de películas desarrollada con FastAPI. Permite a los usuarios registrados realizar reseñas de películas.

## Características

- Registro de usuarios y autenticación mediante JWT (JSON Web Tokens).
- Creación, lectura, actualización y eliminación de reseñas de películas.
- Consulta de películas y reseñas por usuarios específicos.
- Protección de ciertos endpoints que requieren autenticación.

## Requisitos

- Python 3.7 o superior
- Bibliotecas y dependencias especificadas en el archivo `requirements.txt`

## Instalación

1. Clona el repositorio

`git clone https://github.com/MiguelRizzi/fastapi_movie_reviews.git`


2. Crea y activa un entorno virtual

`python3 -m venv venv`

`source venv/bin/activate`


3. Instala las dependencias

`pip install -r requirements.txt`


4. Configura las variables de entorno



5. Inicia el servidor de desarrollo

`uvicorn main:app --reload`

La API estará disponible en http://localhost:8000.

## Documentación de la API

La documentación interactiva de la API se encuentra en http://localhost:8000/docs. Aquí encontrarás información detallada sobre los endpoints disponibles, los modelos de datos y cómo interactuar con la API.
