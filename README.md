# 🚀 Hub Central de Proyectos — Portafolio Académico e Investigaciones

> **Portal Centralizado Monorepo de Entregas, Talleres e Investigaciones Técnicas**  
> Repositorio de autoría propia estructurado bajo una arquitectura de monorepo modular para alojar y centralizar todos mis proyectos, investigaciones y entregas prácticas, desplegado automáticamente en **GitHub Pages**.

[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-22c55e?style=for-the-badge&logo=github)](https://Pytheiller-18.github.io/Hub_Central_de_Proyectos/)
[![Autor](https://img.shields.io/badge/Autor-Pytheiller--18-0284c7?style=for-the-badge&logo=github)](https://github.com/Pytheiller-18)
[![Autoría](https://img.shields.io/badge/Autor%C3%ADa-Propia-8b5cf6?style=for-the-badge)](#)
[![Arquitectura](https://img.shields.io/badge/Arquitectura-Monorepo%20Modular-06b6d4?style=for-the-badge)](https://github.com/Pytheiller-18/Hub_Central_de_Proyectos)

---

## 🌐 Portal Principal y Accesos Directos

El archivo `index.html` en la raíz actúa como **Hub interactivo** para acceder a cada uno de los proyectos y entornos de trabajo. Para explorar o interactuar con cualquier entrega, ingresa directamente a su enlace:

- ⏳ **Línea de Tiempo Tecnológica:** [`./01-linea-de-tiempo/`](./01-linea-de-tiempo/)
- 🧠 **Mapa Conceptual del Sistema de Computación:** [`./02-mapa-conceptual/`](./02-mapa-conceptual/)
- 📦 **Próxima Entrega / Proyecto 03:** [`./03-siguiente-proyecto/`](./03-siguiente-proyecto/)

---

## 📂 Estructura del Proyecto (Monorepo)

```text
Hub_Proyectos/
├── index.html                   <-- Portal principal (Hub con tarjetas y accesos a cada proyecto)
├── README.md                    <-- Documentación del repositorio
├── .gitignore                   <-- Reglas de exclusión de Git
│
├── 01-linea-de-tiempo/          <-- Proyecto: Línea de tiempo interactiva
├── 02-mapa-conceptual/          <-- Proyecto: Mapa conceptual dinámico (Pan & Zoom)
└── 03-siguiente-proyecto/       <-- Módulo base para futuros proyectos
```

---

## 🛠️ Tecnologías y Estándares de Diseño

- **HTML5 Semántico**: Estructura limpia y accesible en todos los módulos.
- **CSS Moderno & Tailwind CSS**: Diseño responsivo, paleta oscura equilibrada (`#0b0f19`), micro-interacciones, efectos visuales de elevación y desenfoque (*glassmorphism*).
- **JavaScript Vanilla**: Lógica pura y eficiente, sin dependencias pesadas de compilación ni librerías externas innecesarias.
- **Rutas Relativas**: Compatibilidad total tanto para navegación local fuera de línea (*offline*) como en servidores estáticos (GitHub Pages).

---

## 💻 Visualización y Despliegue

### 1. En línea (GitHub Pages)
Accede directamente a la versión en producción desplegada:  
👉 **[https://Pytheiller-18.github.io/Hub_Central_de_Proyectos/](https://Pytheiller-18.github.io/Hub_Central_de_Proyectos/)**

### 2. De forma Local (Sin Servidor Requerido)
1. Clona el repositorio:
   ```bash
   git clone https://github.com/Pytheiller-18/Hub_Central_de_Proyectos.git Hub_Proyectos
   ```
2. Entra a la carpeta:
   ```bash
   cd Hub_Proyectos
   ```
3. Abre el archivo `index.html` en cualquier navegador web moderno (Chrome, Edge, Firefox, Brave, Safari).

---

## 📝 Convención de Commits de Git

El repositorio implementa el estándar de **Conventional Commits** para el control de versiones:

```bash
git commit -m "tipo(modulo): breve descripcion del cambio"
```

### Tipos:
- `feat`: Nueva funcionalidad, módulo o componente interactivo.
- `fix`: Corrección de errores en código, enlaces o estilos.
- `docs`: Modificaciones en documentación o contenidos informativos.
- `style`: Ajustes estéticos, espaciados, tipografías o CSS.
- `refactor`: Reorganización de archivos, carpetas o rutas sin alterar la funcionalidad.

### Módulos (Scopes):
- `hub`: Portal principal (`index.html`).
- `linea-de-tiempo`: Módulo `01-linea-de-tiempo/`.
- `mapa`: Módulo `02-mapa-conceptual/`.
- `siguiente-proyecto`: Módulo `03-siguiente-proyecto/`.
- `repo`: Ajustes globales del repositorio o configuración.

---

## 👤 Autoría y Créditos

- **Autor y Desarrollador:** [Pytheiller-18](https://github.com/Pytheiller-18)
- **Tipo de Proyecto:** Proyecto original de autoría propia — Portafolio Monorepo y Hub Central de Proyectos.
