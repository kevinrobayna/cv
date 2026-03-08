# CV

LaTeX source for my resume.

## Prerequisites

Install BasicTeX via Homebrew:

```bash
brew install --cask basictex
```

Install the required LaTeX packages:

```bash
tlmgr update --self
tlmgr install preprint marvosym enumitem fancyhdr titlesec tabularx
```

## Generate PDF

```bash
pdflatex resume.tex
```

## Clean up auxiliary files (optional)

```bash
rm -f resume.aux resume.log resume.out
```
