# Propuestas para el CV y la búsqueda de trabajo

## Cambios ya aplicados en esta versión

- **Formato moderno y legible**: línea de tiempo con fechas a la izquierda, etiquetas de herramientas por cargo y habilidades agrupadas.
- **Fundación Superación de la Pobreza en una sola entrada** ("2015 y 2017"), en vez de dos entradas idénticas.
- **Redacción pulida** sin cambiar los hechos (p. ej. "depuramiento" → "depuración", siglas de la ENUT explicadas).
- **GitHub, Quarto y Git** agregados a habilidades, porque ya los usas en tus proyectos. Si no quieres mostrarlos, bórralos de `datos/cv.yml`.

## Mejoras al contenido (requieren datos que solo tú tienes)

1. **Cuantificar logros.** Es lo que más diferencia un CV. Ejemplos de preguntas para responder:
   - ¿Cuántos registros / viviendas / casos validaste en el Censo 2024? ¿Qué % de reducción de errores?
   - ¿Cuántas personas encuestadas tuvo la ENUT? ¿Cuántos cuestionarios programaste en Survey Solutions?
   - ¿Automatizaste algún proceso que antes era manual? ¿Cuánto tiempo ahorró?
   - Codificación automática de ocupación: ¿qué tasa de acierto alcanzó?
   Formato sugerido: *verbo + qué + resultado medible* ("Automaticé la validación de X en R, reduciendo de 3 días a 2 horas...").
2. **Publicaciones con enlace.** Los documentos técnicos y publicaciones del INE (EME 2025, ENUT, Censo) son públicos: enlazarlos como "Publicaciones seleccionadas" es evidencia concreta de tu trabajo.
3. **Tesis de magíster.** Agregar el título y método de la tesis (tienes el repo `defensa_tesis`): muestra profundidad metodológica.
4. **Docencia / ayudantías.** Tus repos (`ayudantia2_multi`, `clase-curso-morande`, `seminario_ii`) sugieren experiencia docente. Si la tienes, merece una sección propia.
5. **Recortar lo antiguo.** Experiencias de 2014–2017 pueden resumirse en una línea cada una para que el CV quepa en una página y medio, priorizando el INE.
6. **Perfil más específico.** Ajustar las primeras dos líneas a cada postulación (p. ej. "metodólogo de encuestas" vs. "analista de datos").
7. **Certificar el inglés** (TOEFL, IELTS o Cambridge) si apuntas a organismos internacionales.

## Ideas para la búsqueda de trabajo

- **Dónde apuntar con tu perfil** (metodología de encuestas + producción estadística oficial + R):
  - Organismos internacionales: CEPAL, BID, Banco Mundial, PNUD, OIT, UNICEF (oficinas en Santiago), que buscan perfiles de encuestas de hogares y uso del tiempo.
  - Sector público: ministerios con unidades de estudios (Desarrollo Social, Trabajo, Economía, Mujer), Banco Central, Superintendencias, Consejo para la Transparencia.
  - Centros de estudio y universidades: CEP, MIDE UC, Centro de Microdatos U. de Chile, CIIR, COES, DESUC, Criteria, Cadem, Ipsos, Feedback.
  - Sector privado de datos: bancos, retail y aseguradoras (equipos de *analytics* / *customer insights*).
- **Portafolio en GitHub**: fijar 3–4 repos con buen README (este CV, `escuchas_last`, algún análisis de microdatos públicos). Un reporte Quarto publicado con GitHub Pages vale más que listar "R avanzado".
- **Paquete o herramienta en R** para trabajar con microdatos del INE (ENUT, EME): muy visible en la comunidad y demuestra habilidades concretas.
- **LinkedIn alineado con el CV**: mismo titular ("Sociólogo · Magíster en Métodos · Encuestas y producción estadística"), sección *Destacados* con las publicaciones del INE y el portafolio.
- **Comunidad**: R-Ladies / RUG Santiago, LatinR, Sociedad Chilena de Estadística; dar una charla corta sobre Survey Solutions o paradatos te posiciona como especialista.
- **Habilidades que amplían el mercado**: SQL (casi todos los avisos de analista lo piden), Python básico, y muestreo/estimación con `survey` en R si no lo tienes ya en el CV.
- **Versión en inglés del CV**: con `datos/cv.yml` es fácil crear `datos/cv_en.yml` y un parámetro para elegir el idioma.
- **Carta de presentación reutilizable**: plantilla con 3 párrafos (por qué esa institución / qué aportas con un logro medible / cierre), adaptando solo el primero.
