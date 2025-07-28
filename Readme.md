# Prerrequisitos

Para poder levantar y ejecutar este proyecto, necesitarás tener instalado lo siguiente:

• Git: Para clonar el repositorio.

• Node.js y npm: Gestionados preferiblemente con nvm (Node Version Manager). Esto le permitirá instalar y cambiar fácilmente entre diferentes versiones de Node.js.

## Cómo levantar la aplicación desde cero

A continuación, se detallan los pasos para configurar y ejecutar la aplicación:

1. Clonar el repositorio (luego de un fork)

2. Navegar al directorio del proyecto

  cd pagina-demo

3. Gestionar la versión de Node.js con

  Si se utiliza nvm, puedes asegurarte de usar una versión compatible de Node.js.

  nvm install node # Instala la última versión estable de Node.js

  nvm use node     # Usa la última versión estable


4. Instalar dependencias

  npm install

5. Iniciar el servidor de desarrollo

  npm run build

  npm run dev

6. Acceder en un navegador, a la dirección http://localhost:5173 o un puerto similar.
