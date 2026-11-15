# Academic CV

LaTeX sources for Aarne Talman's academic CV and publication list.

| File | Contents |
| --- | --- |
| `talman_aarne_cv.tex` | Curriculum vitae, following the TENK researcher's CV template (Research Council of Finland format, max 3 pages). Also used for the University of Helsinki docent application. |
| `talman_aarne_publications.tex` | Publication list, grouped by Ministry of Education and Culture publication type (A1, A4, G5). |

Text in red (the `\fillin{}` macro) marks details still to be completed.

## Build

```sh
pdflatex talman_aarne_cv.tex
pdflatex talman_aarne_publications.tex
```

or `latexmk -pdf <file>.tex`.
