# CV

This repository contains the LaTeX source for the CV in [`cv.tex`](cv.tex).

## Install LaTeX

On Ubuntu or Debian, install `pdflatex` and the packages used by the document:

```bash
sudo apt update
sudo apt install texlive-latex-extra texlive-fonts-recommended
```

## Compile the PDF

From the repository root, run:

```bash
pdflatex cv.tex
```

The generated PDF will be written to `cv.pdf`. Run the command a second time if
LaTeX reports that references or links need to be regenerated.

## Clean generated files

Compilation also creates auxiliary files. Remove them with:

```bash
rm -f cv.aux cv.log cv.out
```
