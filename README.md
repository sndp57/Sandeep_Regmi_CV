# Sandeep Regmi - Curriculum Vitae

This repository contains the LaTeX source and current compiled PDF of Sandeep Regmi's curriculum vitae.

## Files

- `main.tex`: CV source.
- `output/pdf/Sandeep_Regmi_CV_2026.pdf`: current compiled CV.

## Build

Compile with XeLaTeX and latexmk. Install the LaTeX packages used by `main.tex`, including `fontawesome5`, before building.

```sh
latexmk -xelatex -interaction=nonstopmode -halt-on-error -outdir=output/pdf main.tex
```

In the prepared Codex cloud environment, use the build helper to initialize the local font and cache paths, compile the PDF, and verify its readable text:

```sh
/workspace/.cloud-setup/Sandeep_Regmi_CV/build.sh
```

The prepared cloud environment can build the CV without network access.

The generated `output/pdf/main.pdf` is a temporary build file. The published PDF uses the stable filename `Sandeep_Regmi_CV_2026.pdf`.
