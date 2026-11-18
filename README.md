# Revisión periódica de cartera · Terránea S.A.

Demo interactiva de cuatro alternativas de mejora para la gestión de la cartera de productos y clientes de Terránea S.A.
Curso DN-0111 Gestión de la Innovación y Estrategia Competitiva (UCR), Equipo 5, Grupo 004, II Semestre 2026.

> **DEMO ILUSTRATIVA:** los datos son simulados y no corresponden a cifras reales de Terránea.

## Qué incluye

Informe por páginas con el estilo del Tablero Terranea (tipografía HWT Artz para títulos y cifras, IBM Plex Sans para el texto, IBM Plex Mono para etiquetas; blanco con acento dorado). El menú lateral agrupa las páginas en cuatro bloques:

- **La propuesta:** Qué hace esta herramienta, Resumen, Matriz de selección y Simulación. Comparan las alternativas A, B, C y D.
- **Herramienta C:**
  - **Productos:** mapa de clasificación (Mantener, Revisar, Ajustar, Descontinuar) con filtro estratégico y cliente principal de cada producto.
  - **Clientes:** matriz de la Tabla 7 (Fidelizar, Desarrollar, Ajustar condiciones, Redefinir la relación) y lectura conjunta productos × clientes.
  - **Evaluador de pedidos:** aplica la herramienta a un pedido ficticio y recomienda la mezcla que más rinde en las horas de línea disponibles.
  - **Comité y bitácora:** agenda fija, integrantes (Tabla 8), calendario bimestral según la constancia de sesiones y bitácora (Tabla C2) donde se registran decisiones y se descarga en CSV.
- **Viabilidad:** hoja de ruta de la Tabla 9, horas-persona y riesgos con su mitigación (Tabla 10).
- **Referencia:** Datos (tablas ficticias editables) y Documentación.
- **Panel ⚙ Parámetros:** pesos de la matriz y supuestos de la simulación, configurables en vivo.

## Cómo verla

- **En línea:** abra el enlace de GitHub Pages del repositorio (Settings → Pages).
- **En su computadora:** descargue `index.html` y ábralo con doble clic en el navegador. Necesita internet para cargar los gráficos (Chart.js).

## Cómo editarla

Todo está en un solo archivo: `index.html`.

- **Desde el navegador:** abra `index.html` en GitHub, haga clic en el lápiz (✏️), edite y pulse *Commit changes*. La página publicada se actualiza en uno o dos minutos.
- **Con un editor completo:** en la página del repositorio, presione la tecla `.` para abrir github.dev.

Lo que está en el código:

- Datos del informe: constantes `CRITERIOS`, `ESPERADOS`, `RECURSOS_C`, `INDICADORES`, `RIESGOS_C` y `ACCIONES` (hoja de ruta).
- Datos ficticios iniciales: `PRODUCTOS` y `CLIENTES`.
- Supuestos iniciales de la simulación: `SUP_DEF` y `EXTRA_DEF`.
- Colores, tipografías y modo oscuro: variables CSS en `:root`. La fuente de títulos se carga desde `fonts/HWT-Artz.ttf`; si no está, se usa Archivo.

Pendiente: validación con Gerencia Comercial y prueba con datos reales de al menos cuatro semanas.
