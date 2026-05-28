# Systems Design and Management Article

Projeto para escrever um artigo em estilo arXiv a partir de trabalhos realizados no MIT em Systems Design and Management.

## Estrutura

- `main.tex`: manuscrito principal em LaTeX.
- `sections/`: seções do artigo.
- `references/references.bib`: bibliografia em BibTeX.
- `figures/`: figuras, diagramas e tabelas exportadas.
- `notes/source-map.md`: mapa dos trabalhos do MIT que serão usados no artigo.

## Compilação

Se houver uma distribuição LaTeX instalada:

```bash
latexmk -pdf main.tex
```

Alternativa:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## Próximo Passo

Preencher `notes/source-map.md` com os cursos, papers, projetos e entregáveis do MIT que devem servir de base para o artigo.
