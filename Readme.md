# Proyecto-integrdor-etapa3

## Tecnologías

Esta es una Api desarrollada con nodeJS, Express y Mongo. 
Se instalaron las siguientes librerías:

Cors, para permitir o restringir solicitudes de recursos en el servidor desde dominios diferentes, facilitando la comunicación entre el frontend y el backend que no comparten el mismo origen.

Dotenv, para facilitar la configuración y manejo de variables sensibles (como credenciales de base de datos y claves de API) sin hardcodearlas en el código fuente.

Express, para simplificar el proceso de construcción de servidores y manejo de rutas, peticiones, respuestas y middleware en aplicaciones web.

Express-validator, para verificar y sanitizar los datos de entrada en las solicitudes HTTP para asegurar que cumplan con los requisitos esperados, mejorando la seguridad y robustez de la aplicación.

Mongoose, para facilitar la interacción con MongoDB proporcionando una estructura para los documentos de la base de datos, validación de esquemas, y funcionalidades avanzadas como hooks y consultas.

Multer, para manejar la carga de archivos desde formularios HTML hacia el servidor, permitiendo la gestión y almacenamiento de archivos en aplicaciones web.

Nodemon, para mejorar el flujo de trabajo durante el desarrollo al eliminar la necesidad de reiniciar manualmente el servidor después de cada cambio, aumentando la eficiencia y la productividad del desarrollador.

## Instalación

El primer paso es instalar las dependencias de node, con el siguiente comando, dentro de la carpeta del proyecto:

```
npm install
```
En segunda instancia, crear en la raiz del proyecto un archivo ".env" con los siguientes valores de variables:

```
PORT=3001
DB_URL_CONNECTION=mongodb+srv://ACA-PONER-TU-CONEXION-URL-DE-MONGO-DB.COMPASS.mongodb.net/game-store
BASE_URL=http://localhost:3001
...
```

Finalmente, levantar el servidor con el comando:
```
npm run dev
```