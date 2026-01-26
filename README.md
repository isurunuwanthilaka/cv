# CV Generation Repository - Isuru Nuwanthilaka

This repository automatically generates my professional CV from a LaTeX template.

## Current Position
**Technical Lead - AI** at Rootcode AI

## Features
- LaTeX CV template (`cv/resume.tex`)
- Automated PDF generation via GitHub Actions
- PDF automatically updated when changes are pushed to main branch

## Building the CV Locally

To build the CV locally, you'll need a LaTeX distribution installed:

```bash
cd cv
pdflatex resume.tex
```

## Accessing the CV

The latest PDF is available at: `cv/resume.pdf`

The GitHub Actions workflow automatically rebuilds the PDF when changes are made to the LaTeX source.

