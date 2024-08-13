# Tabla-Spencil


# Proyecto de Gestión de Muebles

Este proyecto incluye una API desarrollada en Node.js y una interfaz de usuario desarrollada con Stencil. A continuación se detallan los pasos para configurar y ejecutar ambos componentes localmente.

## Requisitos

- **Node.js** v14 o superior
- **MySQL** v8.0 o superior
- **npm** (generalmente incluido con Node.js)

## Instalación

### Clonar el Repositorio

```bash
git clone <URL_DEL_REPOSITORIO>
cd A1Programacion
```

### Configuración de la API (Node.js + MySQL)

1. Dirígete al directorio de la API:


2. Instala las dependencias necesarias:

    ```bash
    npm install
    ```

3. Ejecuta las migraciones de la base de datos:

    ```bash
    npm run migrate
    ```

4. Inicia la API:

    ```bash
    npm start
    ```

### Configuración de la Interfaz de Usuario (Stencil)

1. Dirígete al directorio del proyecto de Stencil:

    ```bash
    cd ../componente-01-emespinosa4_espe
    ```

2. Instala las dependencias necesarias:

    ```bash
    npm install
    ```

3. Ejecuta la aplicación en modo de desarrollo:

    ```bash
    npm start
    ```

    Esto abrirá la aplicación en tu navegador por defecto en `http://localhost:3333`.

## Uso

Una vez que ambos componentes estén ejecutándose, puedes interactuar con la aplicación a través de la interfaz de usuario en tu navegador. La API estará disponible en `http://localhost:3000/furniture`.

