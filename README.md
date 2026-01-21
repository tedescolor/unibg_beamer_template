# UNIBG Beamer Template

A (personal) LaTeX Beamer slide template for the University of Bergamo (UNIBG)

## What’s included

* Clean title slide + closing slide layout
* Example slides (tables, equations, figures)
* Bibliography example (`references.bib`)
* Example figure folder (`figures/`)

## Repository structure

* `main.tex` — main Beamer source
* `references.bib` — BibTeX references
* `figures/` — sample images used in the example deck

## Quick start

1. Click **Use this template** on GitHub (or clone the repo).
2. Edit the metadata in `main.tex`:
* `\title{...}`
* `\subtitle{...}`
* `\author{...}`
* `\institute{...}`
* `\date{...}`


3. Replace example sections with your content.

## Use on Overleaf (recommended)

You can directly open and use the template on Overleaf here:

```text
https://www.overleaf.com/read/drxfzbmkcfyp#02a54e

```

## Compile locally


```bash
latexmk -pdf main.tex

```
