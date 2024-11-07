# Proyecto base con NodeJs
Es un proyecto base JavaScript creado con un entorno de ejecución con framework en NodeJs
de código abierto para desarrolladores que necesitan construir una aplicación 
escalable y de alto rendimiento del lado del servidor.

## Versión
`nvm use v19.7.0`

## Instalación
`npm install`

## Librerías iniciales
```json
    "dependencies": {
        "cors": "^2.8.5",
        "dotenv": "^16.4.5",
        "express": "^4.19.2",
        "express-session": "^1.18.0",
        "jsonwebtoken": "^9.0.2",
        "moment": "^2.24.0",
        "mongoose": "^5.13.22",
        "multer": "^1.4.5-lts.1",
        "nodemon": "^3.1.4",
        "passport": "^0.7.0",
        "passport-local": "^1.0.0",
        "passport-local-mongoose": "^8.0.0",
        "puppeteer": "^14.3.0"
    }
```

## Uso de librerías
```json
{
   "cors": "Middleware para ExpressJs que permite habilitar el CORS con varias opciones",
    "dotenv": "Permite cargar variables de entorno desde un archivo .env",
    "express": "Framework para construir API Rest en una aplicación NodeJs",
    "express-session": "Gestión de sesiones para preservar los datos de múltiples solicitudes del mismo cliente",
    "jsonwebtoken": "Generación de token para el cliente",
    "moment": "Permite la manipulación para variables de tipo fecha",
    "mongoose": "Permite crear nuestros modelos de base de datos y conexión hacia la misma",
    "multer": "Middleware para guardar archivos enviados desde el cliente",
    "passport": "Middleware de autenticación",
    "passport-local": "Módulo que permite autenticarse por medio de usuario y contraseña",
    "passport-local-mongoose": "Módulo que permite autenticarse con nombre de usuario y contraseña haciendo el guardado del hash y salt en un esquema de MongoDB",
    "puppeteer": "Generación de PDF desde el servidor"
}
```
