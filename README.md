# ⏳ Línea de Tiempo: Evolución de los Computadores

> **De la Piedra a la Nube Cuántica** — Una investigación exhaustiva sobre la evolución de la arquitectura de computadores: identificando las máquinas, tecnologías y saltos de paradigma que externalizaron el procesamiento humano.

---

## 🚀 Historial de Versiones

### 📌 Versión 3.1 (v3.1.0) — *Actual*
- **Visor Modal Interactivo (Lightbox) HD**: Al hacer clic en cualquier imagen o en el botón dedicado `[Ampliar]`, se abre un visor a pantalla completa con la imagen en alta definición, ficha técnica y notas de investigación histórica detallada.
- **Doble Acceso de Interacción**:
  - Contenedor de imagen con zoom suave al pasar el cursor (`hover:scale-105`) e insignia luminosa `🔍 Clic para ampliar`.
  - Botón directo `[Ampliar]` en la cabecera de cada una de las 17 tarjetas para máxima usabilidad.
- **Navegación Fluida Multiplataforma**:
  - Botones flotantes interactivos de anterior (`❮`) y siguiente (`❯`).
  - Navegación completa por teclado con flechas izquierda (`←`), derecha (`→`) y cierre con tecla `Esc`.
  - Cierre interactivo con botón `✖` o haciendo clic fuera del modal.
- **Almacenamiento Local de Imágenes en HD (`images/`)**: Todas las imágenes fueron descargadas localmente en el repositorio (optimizadas hasta **1280px**), garantizando funcionamiento 100% offline sin depender de servidores externos, caídas de red ni limitaciones de tasa (Rate Limiting 429).
- **Control Estricto de Renderizado**: Se eliminaron conflictos de clases CSS para asegurar que el modal y las tarjetas respondan de forma instantánea y limpia en cualquier navegador.

### 📌 Versión 2.0 (v2.0.0)
- **Fotografía Histórica Real**: Sustitución de los marcadores temporales por imágenes documentales auténticas y diagramas de alta resolución (Wikimedia Commons) para cada uno de los 17 hitos.
- **Consistencia Visual**: Mejoras en la renderización y contraste de imágenes en modo oscuro.

### 📌 Versión 1.0 (v1.0.0)
- Estructura base de la línea de tiempo interactiva (+4000 años de historia computacional).
- Síntesis de los 17 hitos tecnológicos clave desde el Ábaco hasta la computación cuántica.
- Sección de análisis técnico y preguntas reflexivas sobre arquitectura de computadores.
- Interfaz estilizada con Tailwind CSS y paleta futurista en modo oscuro.

---

## 🏛️ Los 17 Hitos Tecnológicos de la Línea del Tiempo

| # | Hito Histórico | Periodo / Año | Tecnología Base | Aporte Principal |
| :-: | :--- | :--- | :--- | :--- |
| **1** | **El Ábaco** | 2700 - 2300 a.C. | Mecánica manual (madera y piedra) | Primer sistema formal de registro y cálculo posicional. |
| **2** | **La Pascalina** | 1642 | Engranajes mecánicos y trinquetes (*sautoir*) | Acarreo decimal continuo automático en sumas y restas. |
| **3** | **Máquina Analítica** | 1837 | Mecánica a vapor y tarjetas perforadas | Separación conceptual entre *Molino* (ALU) y *Almacén* (Memoria). |
| **4** | **Máquina Tabuladora** | 1890 | Electromecánica y contactos de mercurio | Cómputo masivo del censo de EE.UU. y base fundacional de IBM. |
| **5** | **Computadora Z3** | 1941 | 2.300 relés telefónicos electromecánicos | Primera máquina automática con aritmética binaria y coma flotante. |
| **6** | **Colossus** | 1943 - 1944 | Válvulas termoiónicas y sensores ópticos | Procesamiento digital electrónico masivo para descifrado de códigos. |
| **7** | **Arquitectura Von Neumann** | 1945 | Modelo lógico de *Programa Almacenado* | Unificación en memoria de datos e instrucciones; nace el software moderno. |
| **8** | **ENIAC** | 1946 | 17.468 tubos de vacío termoiónicos | Primer ordenador electrónico digital de propósito general (150 kW). |
| **9** | **El Transistor** | 1947 | Semiconductores de estado sólido (Germanio) | Sustitución de tubos de vacío por interruptores de silicio/germanio. |
| **10** | **El Circuito Integrado** | 1958 - 1959 | Litografía planar monolítica en silicio | Solución a la "tiranía de los números" mediante microchips integrados. |
| **11** | **IBM System/360** | 1964 | Módulos lógicos sólidos (SLT) | Compatibilidad de software entre familias y estandarización del byte de 8 bits. |
| **12** | **Intel 4004** | 1971 | Microchip LSI (2.300 transistores pMOS) | Primer microprocesador monolítico comercial en un único chip de 4 bits. |
| **13** | **Altair 8800** | 1975 | CPU Intel 8080 y bus de expansión S-100 | Detonante de la revolución del PC y nacimiento de Microsoft (Altair BASIC). |
| **14** | **IBM PC 5150** | 1981 | Arquitectura x86 abierta (Intel 8088 / MS-DOS) | Estándar dominante de computación personal y clonación limpia de BIOS. |
| **15** | **Procesadores Multi-núcleo** | 2005 - 2006 | Paralelismo a nivel de hilos (TLP) en silicio | Superación del muro térmico mediante múltiples núcleos en un solo chip. |
| **16** | **SoCs Heterogéneos (UMA)** | 2020+ | Litografía 5nm / Memoria Unificada UMA | Integración de CPU, GPU, NPU y RAM en un silicio eficiente (Apple Silicon). |
| **17** | **Supremacía Cuántica** | Actualidad / Futuro | Cúbits superconductores a 15 milikelvin | Superposición y entrelazamiento cuántico para cálculo no lineal masivo. |

---

## 📂 Estructura del Repositorio

```text
Evo_Computadores/
├── images/
│   ├── 01_abaco.png
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
├── .gitignore
├── README.md
└── evoluci_n_de_los_computadores.html
```

---

## 💻 Cómo Visualizar e Interactuar

1. **Clonar o descargar** este repositorio:
   ```bash
   git clone https://github.com/Pytheiller-18/Evo_Computadores.git
   ```
2. **Abrir el archivo**:
   Abre directamente `evoluci_n_de_los_computadores.html` en cualquier navegador web moderno (Google Chrome, Microsoft Edge, Brave, Mozilla Firefox, Safari).
3. **Interactuar con las imágenes**:
   - Haz clic sobre cualquier imagen o en el botón **`[Ampliar]`** para abrir el visor a pantalla completa.
   - Navega usando las flechas de tu teclado `←` / `→` o los botones en pantalla.
   - Cierra el visor con la tecla `Esc` o el botón `✖`.
