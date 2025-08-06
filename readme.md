# Peano: a minimal & modern theme 

**Peano** is a PDFLaTeX-compatible LaTeX Beamer theme developed by myself for use in the CrypTo research group at the *Politecnico di Torino* (Italy), named after the famous Turinese mathematician Giuseppe Peano, also the namesake of our department. The color palette is derived by Prussian Blue, the official color of *Politecnico di Torino*.

<img width="337" height="251" alt="Sample image." src="https://github.com/user-attachments/assets/46571c48-ebb7-49b8-995b-68dc7553ec07" />

## Authoring and Licensing

This theme was created starting from [the excellent answer by **Claudio Fiandrino** on StackOverflow](https://tex.stackexchange.com/questions/146529/design-a-custom-beamer-theme-from-scratch). Inspiration mainly came from [previous Beamer theme by **Giacomo Borin** and myself](https://github.com/giacomoborin/Beamer-Theme) and some of my Microsoft Powerpoint presentations.

The theme is distributed under the **GNU General Public License v3** (or later if available). You may redistribute and/or modify it under the terms of the GPL. No warranty is provided, either expressed or implied.

## Installation and Usage

1. Download the `.sty` files an add them in the root repository of your LaTeX project.
2. Load the theme in your main document:

```latex
\documentclass{beamer}
\usetheme{peano} 
```
2. Define author, date, and other usual stuff:

```latex
\title{Presentation Title}
\author{Author Name}
\date{\today}
```
