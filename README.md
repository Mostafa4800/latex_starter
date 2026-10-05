# LaTeX Starter

A minimal starter template for writing documents with LaTeX.

## Prerequisites

Install a LaTeX distribution:

- **TeX Live** (Linux)
- **MacTeX** (macOS)
- **MiKTeX** (Windows)

## Recommended structure

- `main.tex` – main document entry point
- `sections/` – optional section files
- `assets/` – images and other resources
- `references.bib` – bibliography entries (if used)

## Build document

Compile with:

```bash
pdflatex main.tex
```

If you use bibliography:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## Useful workflow

- Keep content split into section files for easier editing.
- Store figures in `assets/` and reference with relative paths.
- Use labels/references for cross-referencing sections, figures, and tables.
