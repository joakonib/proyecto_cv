# Propuestas para el CV y la búsqueda de trabajo

## Cambios aplicados en esta versión

- **Formato legible por sistemas de selección (ATS)**: una columna, sin tablas ni grillas, títulos de sección estándar ("Experiencia profesional", "Educación"), viñetas, texto seleccionable, fuente estándar (Calibri), URL de LinkedIn escrita completa y metadatos (título, autor, palabras clave) en el PDF.
- **Diseño sobrio** en grises, sin adornos ni etiquetas.
- **Fecha bajo cada cargo**, junto a la institución, en vez de alineada a la derecha.
- **Los tres cargos del INE agrupados** bajo un solo empleador (octubre 2021 – actualidad), para mostrar la progresión.
- **Fundación Superación de la Pobreza en una sola entrada**, en vez de dos idénticas.
- **Viñetas que empiezan con verbos** ("Programé", "Validé", "Elaboré"), sin cambiar los hechos.
- **El Censo como destinación**: se ve la continuidad como Analista Socioeconómico desde 2021 y que te destinaron al Censo como Analista Metodológico Senior.
- **Nombre de cada encuesta en el título del cargo** (EME, Censo 2024, ENUT): son las palabras clave que buscan los filtros.
- **Perfil reescrito con hechos concretos**: años de experiencia, las tres operaciones estadísticas y tus herramientas, en vez de frases genéricas.
- **Archivo `CV_Joaquin_Galdames.pdf`**: es el nombre que ve quien lo descarga.

## Cosas que te propongo cambiar (necesitan tu decisión o datos que solo tú tienes)

1. **Cuantificar logros.** Es lo que más diferencia un CV. Preguntas para responder:
   - ¿Cuántos registros validaste en el Censo 2024? ¿Bajaron los errores?
   - ¿Cuántos hogares o personas tuvo la ENUT? ¿Cuántos módulos programaste en Survey Solutions?
   - ¿Automatizaste algún proceso manual? ¿Cuánto tiempo ahorró?
   - Codificación automática de ocupación: ¿qué tasa de acierto alcanzó?
   Formato: *verbo + qué + resultado* ("Automaticé en R la validación de X, reduciendo el tiempo de 3 días a 2 horas").
2. **Agregar ciudad** ("Santiago, Chile") en el encabezado: muchos filtros de ATS usan la ubicación.
3. **Publicaciones con enlace.** Los documentos técnicos del INE (EME 2025, ENUT, Censo) son públicos: una sección "Publicaciones seleccionadas" es evidencia concreta.
4. **Tesis de magíster** (título y método) y **docencia/ayudantías**, si las tienes.
5. **Resumir la experiencia 2014–2017** a una línea por cargo, para que el CV quepa en una página y media y el foco quede en el INE.
6. **Certificar el inglés** (TOEFL, IELTS o Cambridge) si apuntas a organismos internacionales.
7. **Tener también una versión .docx**: algunos portales (y Trabajando.com / Laborum) leen mejor Word que PDF. Se puede generar desde el mismo `datos/cv.yml`.

## Ideas para la búsqueda de trabajo

- **Dónde apuntar con tu perfil** (encuestas + producción estadística oficial + R):
  - Organismos internacionales en Santiago: CEPAL, BID, Banco Mundial, PNUD, OIT, UNICEF.
  - Sector público: unidades de estudios de ministerios (Desarrollo Social, Trabajo, Economía, Mujer), Banco Central, superintendencias.
  - Centros de estudio y encuestadoras: CEP, MIDE UC, Centro de Microdatos U. de Chile, COES, DESUC, Criteria, Cadem, Ipsos.
  - Sector privado: equipos de analytics o customer insights en bancos, retail y aseguradoras.
- **Adaptar palabras clave a cada aviso**: los ATS comparan el CV con el texto del aviso; repetir sus términos exactos (p. ej. "control de calidad de datos", "muestreo") sube el puntaje.
- **LinkedIn alineado con el CV**: mismo titular y la sección *Destacados* con las publicaciones del INE.
- **Comunidad**: R-Ladies / grupos de R en Santiago, LatinR, Sociedad Chilena de Estadística. Una charla corta sobre Survey Solutions o paradatos te posiciona como especialista.
- **Habilidades que amplían el mercado**: SQL (casi todos los avisos de analista lo piden), Python básico y estimación con diseños complejos (`survey` en R) explícita en el CV.
- **Versión en inglés**: con `datos/cv.yml` es fácil crear `datos/cv_en.yml`.
- **Carta de presentación reutilizable**: 3 párrafos (por qué esa institución / qué aportas con un logro medible / cierre), adaptando solo el primero.
