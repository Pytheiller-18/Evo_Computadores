# 🚀 Hub Central de Proyectos — Portafolio Académico e Investigaciones

> **Portal Centralizado Monorepo de Entregas, Talleres e Investigaciones Técnicas**  
> Un único repositorio estructurado bajo una arquitectura de monorepo modular para alojar todas las entregas académicas, líneas de tiempo interactivas y mapas conceptuales de arquitectura de computadores, desplegado automáticamente en **GitHub Pages**.

[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-22c55e?style=for-the-badge&logo=github)](https://Pytheiller-18.github.io/Hub_Central_de_Proyectos/)
[![Arquitectura](https://img.shields.io/badge/Arquitectura-Monorepo%20Modular-06b6d4?style=for-the-badge)](https://github.com/Pytheiller-18/Hub_Central_de_Proyectos)
[![Licencia](https://img.shields.io/badge/Uso-Acad%C3%A9mico-6366f1?style=for-the-badge)](#)

---

## 🌐 Portal Principal (Hub Central)

El archivo `index.html` en la raíz funciona como **portal centralizador (Hub)** con interfaz gráfica moderna, oscura y responsiva (*cards* interactivas con efectos de elevación e iluminación ambiental). Cada tarjeta representa un proyecto o entrega independiente, permitiendo acceder y evaluar todo el trabajo desde un único enlace raíz:

- ⏳ **Módulo 1 — Línea de Tiempo Tecnológica:** [`./01-linea-de-tiempo/`](./01-linea-de-tiempo/)
- 🧠 **Módulo 2 — Mapa Conceptual del Sistema de Computación:** [`./02-mapa-conceptual/`](./02-mapa-conceptual/)
- 📦 **Módulo 3 — Módulo Base para Futuras Entregas:** [`./03-siguiente-proyecto/`](./03-siguiente-proyecto/)

---

## 📂 Estructura del Proyecto (Monorepo)

```text
Hub_Proyectos/
├── index.html                   <-- Portal principal (Hub con tarjetas y enlaces a cada proyecto)
├── README.md                    <-- Documentación exhaustiva del repositorio y guía de uso
├── .gitignore                   <-- Reglas de exclusión de Git
│
├── 01-linea-de-tiempo/
│   ├── index.html               <-- Proyecto de la línea de tiempo con visor modal HD
│   ├── 01_abaco.png             <-- Activos e ilustraciones de cada hito histórico
│   ├── 02_pascalina.jpg
│   ├── 03_maquina_analitica.jpg
│   ├── 04_tabuladora_hollerith.jpg
│   ├── 05_z3_zuse.jpg
│   ├── 06_colossus.jpg
│   ├── 07_von_neumann.png
│   ├── 08_eniac.jpg
│   ├── 09_transistor.jpg
│   ├── 10_circuito_integrado.png
│   ├── 11_ibm_system360.jpg
│   ├── 12_intel_4004.jpg
│   ├── 13_altair_8800.jpg
│   ├── 14_ibm_pc_5150.jpg
│   ├── 15_multicore.jpg
│   ├── 16_soc_apple_silicon.jpg
│   └── 17_computacion_cuantica.jpg
│
├── 02-mapa-conceptual/
│   └── index.html               <-- Mapa conceptual interactivo (Lienzo virtual Pan & Zoom)
│
└── 03-siguiente-proyecto/
    └── index.html               <-- Módulo base extensible para futuras entregas o laboratorios
```

---

## 🚀 Proyectos y Entregas Integradas

### ⏳ 01. Línea de Tiempo: Evolución de los Computadores (`./01-linea-de-tiempo/`)
- **Investigación Cronológica Exhaustiva:** Análisis de más de 4.000 años de evolución informática divididos en **17 hitos clave**, desde el Ábaco manual hasta la computación cuántica superconductora.
- **Visor Modal Interactivo (Lightbox) HD:** 
  - Ficha técnica completa de cada máquina: contexto cronológico, tecnología base, aporte arquitectónico y salto de paradigma.
  - Almacenamiento 100% local de imágenes optimizadas de alta definición dentro de su propia subcarpeta mediante rutas relativas (`./08_eniac.jpg`).
  - Navegación fluida por teclado (`←`, `→`, `Esc`) y botones táctiles/pantalla.
- **Barra de Navegación del Portafolio:** Retorno inmediato al Hub Central o salto directo al siguiente proyecto.

#### 🏛️ Los 17 Hitos Históricos
| # | Hito Histórico | Periodo / Año | Tecnología Base | Aporte Principal |
| :-: | :--- | :--- | :--- | :--- |
| **1** | **El Ábaco** | 2700 - 2300 a.C. | Mecánica manual (madera y piedra) | Primer sistema formal de registro y cálculo posicional. |
| **2** | **La Pascalina** | 1642 | Engranajes mecánicos y trinquetes (*sautoir*) | Acarreo decimal continuo automático en sumas y restas. |
| **3** | **Máquina Analítica** | 1837 | Mecánica a vapor y tarjetas perforadas | Separación conceptual entre *Molino* (ALU) y *Almacén* (Memoria). |
| **4** | **Máquina Tabuladora** | 1890 | Electromecánica y contactos de mercurio | Cómputo masivo del censo de EE.UU. y base fundacional de IBM. |
| **5** | **Computadora Z3** | 1941 | 2.300 relés telefónicos electromecánicos | Primera máquina automática con aritmética binaria y coma flotante. |
| **6** | **Colossus** | 1943 - 1944 | Válvulas termoiónicas y sensores ópticos | Procesamiento digital electrónico masivo para criptoanálisis. |
| **7** | **Arquitectura Von Neumann** | 1945 | Modelo lógico de *Programa Almacenado* | Unificación en memoria de datos e instrucciones (software moderno). |
| **8** | **ENIAC** | 1946 | 17.468 tubos de vacío termoiónicos | Primer ordenador electrónico digital de propósito general (150 kW). |
| **9** | **El Transistor** | 1947 | Semiconductores de estado sólido (Germanio) | Sustitución de tubos por interruptores de estado sólido de alta velocidad. |
| **10** | **El Circuito Integrado** | 1958 - 1959 | Litografía planar monolítica en silicio | Solución a la "tiranía de los números" mediante microchips integrados. |
| **11** | **IBM System/360** | 1964 | Módulos lógicos sólidos (SLT) | Compatibilidad binaria entre familias y estandarización del byte de 8 bits. |
| **12** | **Intel 4004** | 1971 | Microchip LSI (2.300 transistores pMOS) | Primer microprocesador monolítico comercial en un único chip de 4 bits. |
| **13** | **Altair 8800** | 1975 | CPU Intel 8080 y bus de expansión S-100 | Detonante de la revolución del microordenador personal y Altair BASIC. |
| **14** | **IBM PC 5150** | 1981 | Arquitectura x86 abierta (Intel 8088 / MS-DOS) | Estándar dominante de computación personal y clonación limpia de BIOS. |
| **15** | **Procesadores Multi-núcleo** | 2005 - 2006 | Paralelismo a nivel de hilos (TLP) en silicio | Superación del muro térmico mediante múltiples núcleos en un solo die. |
| **16** | **SoCs Heterogéneos (UMA)** | 2020+ | Litografía 5nm / Memoria Unificada UMA | Integración de CPU, GPU, NPU y RAM en un silicio eficiente (Apple Silicon). |
| **17** | **Supremacía Cuántica** | Actualidad / Futuro | Cúbits superconductores a 15 milikelvin | Superposición y entrelazamiento cuántico para cálculo no lineal masivo. |

---

### 🧠 02. Mapa Conceptual: Sistema de Computación (`./02-mapa-conceptual/`)
- **Lienzo Virtual Interactivo:** Canvas dinámico con soporte nativo para arrastre (*drag & pan*) y controles de zoom (`Zoom In`, `Zoom Out`, `Centrar`).
- **Desglose Estructural Completo:**
  - **Hardware (Soporte Físico):** Procesamiento (CPU, GPU, NPU), Memoria Principal (RAM, ROM, Caché), Almacenamiento Masivo (SSD, HDD), Placa Base y Buses, Periféricos (Entrada, Salida, Mixtos), Soporte de Red y Fuente de Alimentación.
  - **Software (Soporte Lógico):** Software de Sistema (Sistemas Operativos, Controladores), Utilitarios/Diagnóstico, Herramientas de Programación (Compiladores, IDEs, Intérpretes) y Software de Aplicación.
- **Barra de Navegación Rápida:** Acceso instantáneo al Hub Central o a la línea de tiempo.

---

### 📦 03. Próximo Proyecto / Módulo Futuro (`./03-siguiente-proyecto/`)
- Módulo base preconfigurado con el sistema de diseño del Hub para incorporar nuevos talleres, informes de laboratorio o proyectos prácticos sin alterar la configuración del monorepo.

---

## 🛠️ Tecnologías y Estándares de Diseño

- **HTML5 Semántico**: Estructura limpia y accesible en todos los módulos.
- **CSS Moderno & Tailwind CSS**: Diseño responsivo, modo oscuro profundo (`#0b0f19`), paleta HSL balanceada, efectos de cristal (*glassmorphism*) y gradientes sutiles.
- **JavaScript Vanilla**: Rendimiento máximo, cero dependencias pesadas de compilación, compatible de forma nativa con todos los navegadores.
- **Rutas Relativas Puras**: Funcionamiento 100% garantizado tanto en entornos locales sin servidor como en servidores estáticos (GitHub Pages).

---

## 💻 Visualización y Despliegue

### 1. En línea (GitHub Pages)
Accede directamente al portal en producción:  
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
3. Abre el archivo `index.html` en tu navegador preferido (Chrome, Firefox, Edge, Brave, Safari).

---

## 📝 Convención de Commits de Git

El proyecto sigue la convención de **Conventional Commits** para mantener un historial limpio, trazable y profesional:

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

#### Ejemplos:
```bash
git commit -m "feat(hub): integrar nuevas tarjetas interactivas de proyectos"
git commit -m "docs(repo): actualizar documentacion general para Hub Central de Proyectos"
git commit -m "refactor(linea-de-tiempo): optimizar carga de imagenes locales HD"
```
