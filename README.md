# I&M Electric - Proyecto Web Angular

Este documento proporciona instrucciones detalladas para configurar y ejecutar el proyecto web Angular en un entorno local.

## Prerrequisitos

Antes de comenzar, asegúrate de tener instalados los siguientes programas:

- [Node.js](https://nodejs.org/) (Incluye `npm`)
- [Git](https://git-scm.com/)
- [Visual Studio Code (VS Code)](https://code.visualstudio.com/)

## Paso a Paso para Ejecutar el Proyecto

### 1. Descargar e Instalar Visual Studio Code
1. Dirígete al sitio web oficial de [Visual Studio Code](https://code.visualstudio.com/).
2. Descarga el instalador para tu sistema operativo.
3. Sigue las instrucciones para completar la instalación.

### 2. Clonar el Repositorio
1. Abre **Visual Studio Code**.
2. Abre la terminal integrada (`Ctrl + `` o ve a `View > Terminal`).
3. Ejecuta el siguiente comando para clonar el repositorio:
   ```bash
   git clone https://github.com/Ikeroed04060/I-M-ELECTRIC.git
   ```
4. Navega al directorio del proyecto:
   ```bash
   cd I-M-ELECTRIC
   ```

### 3. Instalar Angular CLI
1. Para ejecutar el proyecto Angular, necesitas tener Angular CLI instalado globalmente. Ejecuta el siguiente comando en la terminal:
   ```bash
   npm install -g @angular/cli
   ```

### 4. Instalar Dependencias
1. Asegúrate de que `npm` esté instalado ejecutando:
   ```bash
   npm --version
   ```
   Si no está instalado, descarga e instala [Node.js](https://nodejs.org/).

2. En el directorio del proyecto, ejecuta el siguiente comando para instalar las dependencias del proyecto:
   ```bash
   npm install
   ```

### 5. Ejecutar el Proyecto
1. Una vez instaladas las dependencias, inicia el servidor de desarrollo de Angular:
   ```bash
   ng serve
   ```
2. Abre un navegador web y navega a `http://localhost:4200/` para ver el proyecto en ejecución.

## Notas Adicionales
- Si no tienes instalado Angular CLI, puedes instalarlo globalmente ejecutando:
  ```bash
  npm install -g @angular/cli
  ```




