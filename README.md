# proyecto_cv

CV de Joaquín Galdames generado con Quarto + Typst.

- `datos/cv.yml`: todo el contenido (experiencia, formación, habilidades). Para actualizar el CV, editar solo este archivo.
- `cv.qmd`: diseño. Lee el YAML y arma el PDF.
- `cv.pdf`: resultado.
- `MEJORAS.md`: propuestas para el CV y la búsqueda de trabajo.

## Generar el PDF

```
quarto render cv.qmd
```

Requiere R con el paquete `yaml`. Typst viene incluido en Quarto, no hace falta LaTeX.
