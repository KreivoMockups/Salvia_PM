# Ecosistema SALVIA - Panorama Consolidado (Etapa 2)

![Estado: Operativo](https://img.shields.io/badge/Estado-Operativo-success)
![Cliente: MinIgualdad](https://img.shields.io/badge/Cliente-Ministerio_de_Igualdad_y_Equidad-purple)

Este repositorio contiene la vista ejecutiva (Dashboard) del estado de avance, arquitectura y hoja de ruta del proyecto **SALVIA** (Sistema Nacional de Registro, Atención, Seguimiento y Monitoreo de las Violencias Basadas en Género) en su Etapa 2. 

El objetivo de esta interfaz es proporcionar a los *stakeholders* y al equipo de desarrollo una visión clara, estructurada y en tiempo real de lo que ya opera, lo que sigue en construcción y lo que falta por resolver antes del cierre contractual.

## 🎯 Características Principales

La interfaz está dividida en cuatro bloques estratégicos:

*   **Métricas de Progreso:** Indicadores en tiempo real del avance físico y el consumo de la bolsa de horas (Bolsa 1 y Bolsa 2).
*   **Estado de Módulos (Tres Capas):** Listado detallado de los 11 módulos del ecosistema (Registro, Seguimiento, Barreras, MASP, etc.) con sus respectivas insignias de estado (Operativo, Completado, En desarrollo, Mockup).
*   **Arquitectura y Entidades:** Diagramas de flujo y conectividad que explican cómo interactúan las fuentes múltiples, la base de datos (EAV-DAG) y los actores externos (ICBF, Fiscalía, MinSalud).
*   **Hoja de Ruta (Roadmap):** Un *backlog* priorizado en tres horizontes de tiempo (Esta semana, Antes del cierre contractual, y Próximos meses).

## 🛠️ Tecnologías Utilizadas

Este dashboard fue construido bajo principios de minimalismo y alta velocidad de carga, sin dependencias de *frameworks* pesados:

*   **HTML5:** Estructura semántica.
*   **CSS3:** Uso de CSS Grid y Flexbox para el sistema de columnas, tarjetas y diagramas interactivos.
*   **JavaScript (Vanilla):** Animaciones ligeras para las barras de progreso.

## 🚀 Instalación y Uso

Dado que el proyecto es un archivo estático, no requiere un proceso de construcción (*build process*) ni instalación de dependencias (NPM/Yarn).

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/tu-usuario/panorama-salvia.git](https://github.com/tu-usuario/panorama-salvia.git)
    ```
2.  **Archivos requeridos:**
    Asegúrate de que la imagen de la arquitectura (`02_2_Salvia.png`) se encuentre en el mismo directorio raíz que el archivo `index.html`.
3.  **Ejecución:**
    Simplemente abre el archivo `index.html` en cualquier navegador web moderno (Chrome, Firefox, Safari, Edge).

## 📊 Estructura de Archivos

```text
/
├── index.html          # Código principal (HTML + CSS + JS embebido)
├── 02_2_Salvia.png     # Asset: Diagrama de arquitectura de datos
└── README.md           # Documentación del proyecto
