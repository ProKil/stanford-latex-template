# Stanford LaTeX Template

A clean, professional LaTeX template for Stanford University academic papers and technical reports.

## Features

- Professional academic paper layout
- Stanford branding with university logo
- Customizable headers and footers
- Support for various document options (two-column, numbering, etc.)
- Clean typography using TeX Gyre Pagella and Math Pazo fonts
- Hyperlinked references and citations
- Compatible with modern LaTeX distributions

## Quick Start

### Basic Usage

```latex
\documentclass[11pt, a4paper, logo]{stanford}

\title{Your Paper Title}
\author{Your Name\\Stanford University}

\begin{document}
\maketitle

\begin{abstract}
Your abstract here.
\end{abstract}

\section{Introduction}
Your content here.

\end{document}
```

### Compiling

```bash
pdflatex example.tex
```

## Class Options

- `11pt`, `10pt`, `12pt`: Set font size (default: 11pt)
- `a4paper`: Paper size
- `twocolumn`: Two-column layout
- `logo`: Include Stanford logo in header
- `nonumbering`: Use unnumbered sections
- `address`: Add postal address in footer
- `copyright`: Add copyright statement

## Files Included

- `stanford.cls` - Main LaTeX class file
- `fancyhdr.sty` - Header/footer styling
- `stanford_logo-eps-converted-to.pdf` - Stanford logo
- `example.tex` - Example document

## Requirements

- LaTeX distribution (TeX Live, MiKTeX, etc.)
- Packages: natbib, microtype, hyperref, graphicx, booktabs, and others (most are standard)

## License

This template is based on the Google DeepMind LaTeX template and is released under the Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) license.

## Credits

Original template: Google DeepMind LaTeX Template  
Adapted by: Hao Zhu, Stanford University

## Support

For issues or questions, please open an issue on GitHub.
