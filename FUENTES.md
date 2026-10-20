# Fuentes

Maestro de fuentes del proyecto: de dónde sale el contenido del CV y en qué se basan las decisiones de formato.

## Contenido

| Fuente | Qué se toma | Dónde se usa |
|---|---|---|
| `input/CV Joaquín Galdames.docx` (copia del Word en Dropbox) | Toda la información: cargos, fechas, funciones, formación, habilidades, idiomas, contacto y la redacción del perfil | `datos/cv.yml` |
| Correcciones de Joaquín (20-10-2026) | El Censo 2024 fue una destinación; la EME actual es la VIII y la IX está en preparación; la encuesta de uso del tiempo es la II ENUT (2025); agregar "Santiago, Chile"; no mostrar GitHub en el contacto | `datos/cv.yml` |

## Formato y recomendaciones

| Fuente | Qué se toma | Dónde se usa |
|---|---|---|
| Buenas prácticas generales para sistemas de seguimiento de postulantes (ATS) | Una columna, sin tablas, títulos de sección estándar, texto seleccionable, fuente estándar, URLs completas, metadatos del PDF | `cv.qmd` |
| [Documentación de Typst](https://typst.app/docs/) y [Quarto + Typst](https://quarto.org/docs/output-formats/typst.html) | Generación del PDF | `cv.qmd` |

## Decisiones propias (no vienen de una fuente)

- Agrupar los tres cargos del INE bajo un solo empleador.
- Resumir la experiencia 2014–2019 en "Experiencia previa", una línea por cargo, para que el CV quepa en una página.
- Viñetas que empiezan con verbo, sin cambiar los hechos del Word.
- Paleta en grises, sin azul.
