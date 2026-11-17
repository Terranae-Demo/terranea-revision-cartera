# Revisión periódica de cartera · Terránea S.A.

Demo interactiva de cuatro alternativas de mejora para la gestión de la cartera de productos y clientes de Terránea S.A.
Curso DN-0111 Gestión de la Innovación y Estrategia Competitiva (UCR), Equipo 5, Grupo 004, II Semestre 2026.

> **DEMO ILUSTRATIVA:** los datos son simulados y no corresponden a cifras reales de Terránea.

## Qué incluye

Informe por páginas con estilo de tablero BI:

- **Resumen, Matriz, Simulación, Productos y clientes, Bitácora, Recursos y riesgos.**
- **Datos:** tablas ficticias de productos y clientes, editables; todo se recalcula al instante.
- **Documentación:** contexto, modelo de datos, medidas, parámetros, indicadores y riesgos.
- **Panel ⚙ Parámetros:** pesos de la matriz y supuestos de la simulación, configurables en vivo.

## Cómo verla

- **En línea:** abra el enlace de GitHub Pages del repositorio (Settings → Pages).
- **En su computadora:** descargue `index.html` y ábralo con doble clic en el navegador. Necesita internet para cargar los gráficos (Chart.js).

## Cómo editarla

Todo está en un solo archivo: `index.html`.

- **Desde el navegador:** abra `index.html` en GitHub, haga clic en el lápiz (✏️), edite y pulse *Commit changes*. La página publicada se actualiza en uno o dos minutos.
- **Con un editor completo:** en la página del repositorio, presione la tecla `.` para abrir github.dev.

Lo que está en el código:

- Datos del informe: constantes `CRITERIOS`, `ESPERADOS`, `RECURSOS_C`, `INDICADORES` y `RIESGOS_C`.
- Datos ficticios iniciales: `PRODUCTOS` y `CLIENTES`.
- Supuestos iniciales de la simulación: `SUP_DEF` y `EXTRA_DEF`.
- Colores y modo oscuro: variables CSS en `:root`.

Pendiente: validación con Gerencia Comercial y prueba con datos reales de al menos cuatro semanas.
