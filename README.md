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
<img width="975" height="517" alt="image" src="https://github.com/user-attachments/assets/e7321e35-eac3-4b3d-84a5-0e87b61a8b06" />
<img width="975" height="518" alt="image" src="https://github.com/user-attachments/assets/1314cb12-def7-4f0e-bfa3-ac6ba8c1e819" />
<img width="975" height="515" alt="image" src="https://github.com/user-attachments/assets/352d141b-e7f7-411c-94fb-56562411c6f3" />
<img width="975" height="518" alt="image" src="https://github.com/user-attachments/assets/29be45ea-c8d5-40c8-a4de-2e61597c60d2" />




