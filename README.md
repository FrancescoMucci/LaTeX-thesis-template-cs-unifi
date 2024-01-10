# LaTeX Template for Computer Science thesis at UniFI

This repository hosts a LaTeX template designed for either Bachelor's or Master's theses in Computer Science at the [University of Florence (UniFI)](https://www.unifi.it/).

I developed this template for my own Master's thesis starting from [the one provided by my degree course](https://www.informaticamagistrale.unifi.it/vp-17-per-laurearsi.html) which in turn was crafted using the [`classicthesis`](https://www.ctan.org/pkg/classicthesis) package, created by [André Miede](https://www.miede.de/), as a basis.

## How to generate the PDF of this thesis template?

To generate the PDF associated with this thesis template, you can execute the following commands in the root directory of the git repository:
```bash
pdflatex -interaction=nonstopmode thesis-template.tex && \
bibtex thesis-template.aux && \
pdflatex -interaction=nonstopmode thesis-template.tex && \
pdflatex -interaction=nonstopmode thesis-template.tex
```
These commands were tested using pdfTeX 3.14159265-2.6-1.40.18 (TeX Live 2017/Debian).
