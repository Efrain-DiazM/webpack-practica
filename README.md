# Curso Webpack - Optimización y Configuración de Proyectos JavaScript

Este repositorio contiene una guía detallada para aprender Webpack desde la configuración básica hasta la optimización avanzada.

## 📌 Objetivo del Proyecto

El objetivo de esta práctica es que los estudiantes aprendan a configurar Webpack en un proyecto JavaScript, modularizar el código, gestionar assets, optimizar la carga y mejorar el rendimiento de las aplicaciones web.

## 📂 Estructura del Proyecto

```sh
curso-webpack/
│── src/
│   ├── index.js
│   ├── utils/
│   │   ├── sum.js
│   ├── styles/
│   │   ├── main.css
│   ├── assets/
│   │   ├── images/
│── public/
│   ├── index.html
│── dist/ (Generado automáticamente por Webpack)
│── webpack.config.js
│── .babelrc
│── package.json
│── README.md
```

## 🚀 Instalación y Configuración

Clona este repositorio y sigue los pasos para configurar Webpack:

```sh
git clone https://github.com/tuusuario/curso-webpack.git
cd curso-webpack
npm install
```

## 🛠️ Uso de Webpack

### 1. Compilar en modo desarrollo:
```sh
npm run dev
```

### 2. Compilar en modo producción:
```sh
npm run build
```

### 3. Ejecutar Webpack manualmente:
```sh
npx webpack --mode development
npx webpack --mode production
```

## 🔧 Tecnologías Utilizadas

- **Webpack** - Empaquetador de módulos
- **Babel** - Transpilador de JavaScript
- **HTML Webpack Plugin** - Generación de HTML dinámico
- **MiniCSSExtractPlugin** - Optimización de CSS
- **Copy Webpack Plugin** - Gestión de archivos estáticos
- **Dotenv Webpack** - Manejo de variables de entorno

## 📜 Licencia

Este proyecto está bajo la licencia MIT.

