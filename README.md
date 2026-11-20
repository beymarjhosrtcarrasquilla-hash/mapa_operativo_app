# Mapa Operativo Visual

Aplicación web interactiva y autocontenida para visualizar, navegar y editar en vivo el flujograma operativo personal mediante **Mermaid.js**.

## Características

- **Estética oscura** (`#0d1117`) con acentos en cian (`#00e5ff`) diseñada para lectura prolongada.
- **Zoom de alta precisión** (10% hasta **2500%**) mediante rueda del ratón o botones `+/-`, además de paneo por arrastre.
- **Enfoque rápido por módulos** desde la barra superior: `Inicio`, `Trabajo`, `Estudio`, `Analizar`, `Repasar`, `Entendimiento`, `Ordenar`, `Escribir` e `Investigar`.
- **Doble clic inteligente** sobre cualquier nodo o subgrafo para centrar y ajustar el zoom automáticamente.
- **Editor Mermaid sincronizado en vivo** (`Editar / Agregar`) para modificar o ampliar el diagrama al instante.

## Estructura del diagrama incluido

- **Inicio** (`Inicio` -> decisión principal)
- **Clase Trabajo** (YouTube, ON RAD4R / Estampado, Clases de música, Servicio técnico, Motorratón / Rappi)
- **Apartado Personal**
- **Apartado Productivo**
- **class Estudio** y sus 6 subprocesos:
  1. `AnalizarInforma`
  2. `Método Repasar`
  3. `Entendimiento`
  4. `OrdenarTexto`
  5. `Escribir`
  6. `Investigar`

## Uso

1. Abre `index.html` directamente en cualquier navegador web moderno (no requiere servidor ni compilación).
2. Usa los botones superiores para saltar a cada módulo o haz doble clic en un nodo para enfocarlo.
3. Haz clic en **Editar / Agregar** para abrir el panel de código Mermaid en vivo.

## Extensibilidad futura

La estructura del proyecto está lista para incorporar nuevos subsistemas (como **Radar** y **Actividades Libres**) agregando subgrafos adicionales en `index.html` o integrando módulos complementarios en este repositorio.
