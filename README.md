# Aplicación CRUD con Python, Flask y MongoDB

## Estructura del proyecto
- `app.py`: Rutas del servidor web y operaciones CRUD (Crear, Leer, Actualizar y Eliminar) en el puerto `4000`.
- `database.py`: Configuración de conexión local hacia MongoDB (`mongodb://localhost:27017/`).
- `product.py`: Clase modelo para estructurar los documentos BSON/JSON de la colección `products`.
- `templates/index.html`: Interfaz de usuario responsiva construida con Bootstrap 5 y plantillas Jinja2.

## Ejecución local
1. Instalar dependencias: `py -m pip install flask pymongo`
2. Asegurar que el servicio local de MongoDB esté activo en el puerto `27017`.
3. Ejecutar el servidor: `py app.py` y abrir `http://localhost:4000` en el navegador.
