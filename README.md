# C12-23-t-java-react-inventory

## Proyecto gestion de inventario
Este proyecto utiliza Docker Compose para facilitar la configuración y ejecución de los servicios necesarios. Antes de levantar el Docker Compose, asegúrate de seguir los pasos a continuación para preparar el entorno.

### Prerrequisitos
- Docker y Docker Compose deben estar instalados en tu sistema.

### Pasos de configuración
- Crear un archivo **.env** y agregar las variables de entorno que requiera el archivo docker compose, puede guiarse del archivo **.example.env**.
- Crea la carpeta **mysqlDB** en el directorio raíz del proyecto: La carpeta mysqlDB se utilizará como un volumen de enlace para la imagen de MySQL. Asegúrate de tener los datos de la base de datos u otros archivos necesarios dentro de esta carpeta.
- Ejecuta el siguiente comando en el directorio raíz del proyecto: **docker-compose up**
- Si deseas detener los servicios y eliminar los contenedores creados, puedes ejecutar el siguiente comando en otra terminal en el mismo directorio raíz del proyecto: **docker-compose down**