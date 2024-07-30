# Proyecto Libreta de Direcciones

Esta es una aplicación sencilla de libreta de direcciones construida utilizando React para el frontend y Node.js para el backend. La libreta de direcciones permite a los usuarios agregar, ver y eliminar información de contactos.

## Tabla de Contenidos
- [Características](#características)
- [Requisitos Previos](#requisitos-previos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Tecnologías](#tecnologías)
- [Contribuyendo](#contribuyendo)
- [Licencia](#licencia)

## Características

- Agregar nuevos contactos con nombre y número de teléfono.
- Ver una lista de todos los contactos.
- Eliminar contactos de la libreta de direcciones.
- Diseño responsivo para una mejor experiencia de usuario en diferentes dispositivos.

## Requisitos Previos

Antes de comenzar, asegúrate de cumplir con los siguientes requisitos:

- Tener Node.js y pnpm instalados en tu máquina.
- Tener MongoDB instalado y en funcionamiento.

## Instalación

1. Clona el repositorio:
    ```sh
    git clone https://github.com/tu-usuario/phonebook.git
    ```

2. Navega al directorio del proyecto:
    ```sh
    cd phonebook
    ```

3. Instala las dependencias del backend:
    ```sh
    cd backend
    pnpm install
    ```

4. Instala las dependencias del frontend:
    ```sh
    cd ../frontend
    pnpm install
    ```

## Uso

### Ejecutar el Servidor Backend

1. Navega al directorio del backend:
    ```sh
    cd backend
    ```

2. Crea un archivo `.env` y añade tu cadena de conexión de MongoDB:
    ```env
    MONGODB_URI=tu_cadena_de_conexión_de_mongodb
    ```

3. Inicia el servidor backend:
    ```sh
    pnpm start
    ```

   El servidor backend se ejecutará en `http://localhost:5000`.

### Ejecutar la Aplicación Frontend

1. Navega al directorio del frontend:
    ```sh
    cd ../frontend
    ```

2. Inicia el servidor de desarrollo de React:
    ```sh
    pnpm start
    ```

   La aplicación frontend se ejecutará en `http://localhost:3000`.

## Tecnologías

- Frontend: React, CSS
- Backend: Node.js, Express
- Base de Datos: MongoDB

## Endpoints de la API

Para revisar los endpoints de la API, consulta el archivo en la carpeta `backend/requests/api.http`.

## Contribuyendo

¡Las contribuciones son siempre bienvenidas! Por favor, sigue estos pasos para contribuir:

1. Haz un fork del repositorio.
2. Crea tu rama de característica:
    ```sh
    git checkout -b feature/TuCaracteristica
    ```
3. Realiza tus cambios y haz un commit:
    ```sh
    git commit -m 'Agrega una característica'
    ```
4. Empuja a la rama:
    ```sh
    git push origin feature/TuCaracteristica
    ```
5. Abre un pull request.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT - mira el archivo [LICENSE](LICENSE) para más detalles.