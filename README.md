<div align="center">

# Markdown Beamer Template

![Pandoc](https://img.shields.io/badge/Pandoc-Beamer-purple)
![XeLaTeX](https://img.shields.io/badge/engine-XeLaTeX-green)

A Markdown-to-PDF Beamer presentation template using Pandoc and the Metropolis
theme, featuring New Computer Modern fonts with full CJK (Chinese) support
via XeLaTeX.

</div>

## Features

- **Theme**: Metropolis (modern, minimalist)
- **Fonts**: New Computer Modern (serif, sans, math) + Source Han (CJK serif, sans)
- **CJK Support**: xeCJK with bundled font files (git submodule)
- **Bibliography**: pandoc-citeproc with CSL styles
- **Editor**: Markdown Preview Enhanced support (export on save)

## Usage

```bash
# Clone with fonts submodule
git clone --recurse-submodules git@github.com:houchen-li/markdown-beamer-template.git

# Build with Pandoc
pandoc main.md -o main.pdf --pdf-engine=xelatex --include-in-header=header.tex

# Or use Markdown Preview Enhanced in VS Code / Atom
```

## Project Structure

```
├── main.md           # Main document (with YAML metadata)
├── header.tex        # LaTeX header (CJK sans font)
├── doc_prefix.tex    # LaTeX prefix
├── doc_suffix.tex    # LaTeX suffix
├── .latexmkrc        # latexmk configuration
├── refs/
│   ├── bibliography.bib
│   └── american-physics-society.csl
├── figures/          # Figures directory
└── fonts/            # Font files (git submodule)
```

## License

BSD 3-Clause
