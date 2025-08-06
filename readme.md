# Peano: a minimal & modern Beamer theme 

**Peano** is a PDFLaTeX-compatible Beamer theme developed by myself, and possibly others in the future, for use in the CrypTo research group at the *Politecnico di Torino* (Italy). The theme is named after the famous Turinese mathematician Giuseppe Peano, also the namesake of our department. 

**Compliance.** The color palette is derived from ![Prussian Blue](https://img.shields.io/badge/Color-Prussian%20Blue-001e3c?style=flat&labelColor=001e3c&color=001e3c)
, the new institutional color of *Politecnico di Torino*. Logos and corporate imagery from *Politecnico di Torino* were adopted in accordance with [their most recent legal guidelines](https://www.polito.it/en/polito/about-us/corporate-image). However, the formal request for imagery use is still pending.

<p align="center">
  <img src="https://github.com/user-attachments/assets/5ef6915f-850e-4ee4-add5-44e3b253814a"width="432" alt="Example cover" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/ef8179c9-1c26-4c27-bb0b-6b719a9f5dcb" width="30%" alt="Example 1." />
  <img src="https://github.com/user-attachments/assets/4ad98238-4f5b-42ab-9c84-bc031c42a64a" width="30%" alt="Example 2." />
  <img src="https://github.com/user-attachments/assets/14031e18-b563-4c03-83e7-32f9944c0864" width="30%" alt="Example 3." />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/LaTeX-Project%20Public%20License-blue.svg" alt="LaTeX Badge" />
  <img src="https://img.shields.io/badge/Beamer-Theme-orange.svg" alt="Beamer Badge" />
  <img src="https://img.shields.io/badge/License-GPLv3-blue.svg" alt="License: GPL v3" />
</p>


## Authoring and Licensing

This theme was created starting from [the excellent answer by **Claudio Fiandrino** on StackOverflow](https://tex.stackexchange.com/questions/146529/design-a-custom-beamer-theme-from-scratch). Inspiration mainly came from [a Beamer theme by **Giacomo Borin** and **Leonardo Errati** (myself)](https://github.com/giacomoborin/Beamer-Theme).

The theme is distributed under the **GNU General Public License v3** (or later if available). You may redistribute and/or modify it under the terms of the GPL. No warranty is provided, either expressed or implied.

## Installation and Usage

1. Download the `.sty` files an add them in the root repository of your LaTeX project.
2. Load the theme in your main document:
```latex
\documentclass{beamer}
\usetheme{peano} 
```

3. Define author, date, and other metadata.
```latex
\title{Presentation Title}
\author{Author Name}
\date{Date}
```

## Q&A

#### Q: *Can I edit the colours of the theme?*
A: They can be modified in `beamercolorthemepeano.sty` style file via their HEX values.

#### Q: *Can it be used for other groups/departments in Politecnico di Torino?*
A: That is possible via removal of the CrypTo logos from `beamerouterthemepeano.sty` and `beamerinnerthemepeano.sty`, then substituting them with the desired logos (or none at all). I reckon I will probably add support for integrating any logos via package options, but that will require some time.

#### Q: *Isn't the footer small?*
A: Indeed. Support for shortened author, title, date fields (e.g. `\date[EC26]{Eurocrypt 2026}`) is intentionally not implemented: simplicity is a feature. Although I might add some customization via package options in the future.
