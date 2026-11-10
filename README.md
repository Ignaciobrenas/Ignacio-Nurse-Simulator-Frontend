# Nurse Simulator Frontend — Parte Individual

<div align="center">

[![Angular](https://img.shields.io/badge/Angular-22.2-DD0031?style=for-the-badge&logo=angular&logoColor=white)](https://angular.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-24-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

</div>

---

> [!IMPORTANT]
> **Entrega individual:**
> Este repositorio contiene mi **parte individual del Nurse Simulator Frontend**, desarrollada por **Ignacio Breñas** dentro del Proyecto Intermodular del Ciclo Formativo de Grado Superior en Desarrollo de Aplicaciones Web (**DAW MP06/MP16**, curso 2025-26) en **STUCOM Pelai**.
>
> Corresponde a la inicialización, estructuración y configuración del entorno cliente con **Angular CLI**, sirviendo como base individual para la posterior integración con el backend hospitalario y el desarrollo colaborativo grupal.

---

## 🔗 Repositorios Relacionados

* **Repositorio Grupal Frontend:** [Ignaciobrenas/Nurse-Simulator-Frontend](https://github.com/Ignaciobrenas/Nurse-Simulator-Frontend)
* **Repositorio Individual Backend (Symfony / Doctrine):** [Ignaciobrenas/Ignacio-Nurse-Simulator](https://github.com/Ignaciobrenas/Ignacio-Nurse-Simulator)
* **Repositorio Grupal Backend:** [Ignaciobrenas/Nurse-Simulator](https://github.com/Ignaciobrenas/Nurse-Simulator)

---

## 📌 Descripción del Proyecto

Este espacio de trabajo contiene la estructura estándar y limpia autogenerada mediante **Angular CLI**, preparada para seguir el flujo de desarrollo de la práctica **PR06 (Introducció al Front-End)**:

* **Arquitectura moderna:** Aplicación basada en componentes standalone y control de flujo declarativo.
* **Enrutamiento:** Soporte nativo para enrutamiento (`@angular/router`) configurado en `app.routes.ts`.
* **Testing:** Entorno configurado con [Vitest](https://vitest.dev/) para pruebas unitarias.
* **Estilos:** CSS estándar con aislamiento por componente.

---

## 📂 Estructura de Archivos del Proyecto

El repositorio mantiene estrictamente los archivos autogenerados por Angular CLI:

```
Ignacio´s Nurse-Simulator Frontend/
├── .vscode/                     # Configuración de depuración y tareas en VS Code
│   ├── extensions.json
│   ├── launch.json
│   └── tasks.json
├── public/                      # Recursos estáticos de la aplicación
│   └── favicon.ico
├── src/
│   ├── app/                     # Código de la aplicación Angular
│   │   ├── app.component.css    # Estilos del componente principal
│   │   ├── app.component.html   # Template HTML del componente principal
│   │   ├── app.component.spec.ts# Pruebas unitarias del componente principal
│   │   ├── app.component.ts     # Lógica y definición del componente raíz
│   │   ├── app.config.ts        # Proveedores y configuración global (rutas)
│   │   └── app.routes.ts        # Definición de rutas del enrutador
│   ├── index.html               # Documento HTML contenedor
│   ├── main.ts                  # Punto de entrada y arranque de la aplicación
│   └── styles.css               # Estilos globales
├── .editorconfig                # Consistencia de formato de código
├── .gitignore                   # Exclusiones de Git para Angular y Node
├── .prettierrc                  # Reglas de formateo de código
├── angular.json                 # Configuración de compilación y CLI de Angular
├── package.json                 # Dependencias y scripts de npm
├── tsconfig.json                # Configuración base de TypeScript
├── tsconfig.app.json            # Configuración de compilación para la aplicación
└── tsconfig.spec.json           # Configuración de TypeScript para pruebas
```

---

## 🚀 Instalación y Puesta en Marcha

### Prerrequisitos

* **Node.js**: versión LTS (v20 o superior).
* **npm**: gestor de paquetes de Node.
* **Angular CLI** instalado globalmente:
  ```bash
  npm install -g @angular/cli
  ```

### Ejecución en Local

```bash
# 1. Clonar el repositorio
git clone https://github.com/Ignaciobrenas/Ignacio-Nurse-Simulator-Frontend.git
cd Ignacio-Nurse-Simulator-Frontend

# 2. Instalar dependencias
npm install

# 3. Iniciar el servidor local de desarrollo
ng serve
# O alternativamente:
npm start
```

Abre tu navegador en `http://localhost:4200/`. La aplicación se recargará automáticamente al modificar los archivos fuente.

### Compilación para Producción

```bash
ng build
```

Los artefactos optimizados se generarán en la carpeta `dist/`.

### Ejecutar Pruebas Unitarias

```bash
ng test
```

---

## 👤 Autor

* **Ignacio Breñas** ([@Ignaciobrenas](https://github.com/Ignaciobrenas))  
  *Ciclo Formativo de Grado Superior en Desarrollo de Aplicaciones Web (DAW 2)*  
  *STUCOM Centre d'Estudis — Barcelona, 2025-26*
