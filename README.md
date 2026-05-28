# Systems Design and Management Article

Project for writing an arXiv-style article based on MIT Systems Design and Management work.

## Structure

- `main.tex`: main LaTeX manuscript.
- `sections/`: article sections.
- `references/references.bib`: BibTeX bibliography.
- `references/bibliography.md`: human-readable bibliography.
- `figures/`: exported figures, diagrams, and tables.
- `notes/source-map.md`: map of MIT work used in the article.
- `opportunity-sets/`: MIT SDM opportunity-set source materials.

## Compilation

If a LaTeX distribution is installed:

```bash
latexmk -pdf main.tex
```

Alternative:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## Next Step

Fill `notes/source-map.md` with the MIT courses, papers, projects, and deliverables that should support the article.
