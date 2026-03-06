**API Biblioteca**

Esta API permite gestionar autores, libros y préstamos mediante endpoints REST.

**Requisitos**

Antes de ejecutar el proyecto se necesita tener instalado:

-Docker

Puedes verificar la instalación con:
docker --version

**Construir la imagen**

Para construir la imagen Docker debes ejecutar el siguiente comando desde la raíz del proyecto:
docker build -t api/biblioteca .

**Ejecutar el contenedor**

Para ejecutar el contenedor:
docker run -it -d -p 3000:3000 -e PORT=3000 api/biblioteca

**Variables de entorno usadas**

La aplicación utiliza las siguientes variables de entorno:
PORT               3000

**Pruebas rápidas con curl**

Ejemplo de requests para probar los endpoints.
curl http://localhost:3000/author
curl http://localhost:3000/books
curl http://localhost:3000/loan
