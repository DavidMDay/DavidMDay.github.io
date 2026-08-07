# English Translation: Maximillian Julius Otto Strutt (1933) 

An independent, open-source English translation of Maximillian Strutt's 1933 paper on conical shell vibration.

*   **Original Title:** *Eigenschwingungen einer Kegelschale*
*   **Original Publication:** *Annals of Physics, Berlin* Volume 409, Issue 7, 1933, pp. 729–735.
*   **Translator:** David M. Day

---

## 📄 Project Overview
This repository contains the full LaTeX source code and the compiled PDF for a modern English translation of Maximillian Julius Otto Strutt's 1933 paper. The goal of this project is to provide a clean, highly readable, and mathematically precise translation for students and researchers.  During the preparation of this work, the author(s) used Google Gemini (Version 3.5).

### Repository Structure
*   `main.tex` — The primary LaTeX source file (uses `amsart` document class).
*   `references.bib` — The BibLaTeX file linking back to the original German metadata.
*   `strutt1933translation.pdf` — The compiled, print-ready PDF version.
*   `Makefile` — for compilation

---

## ⚖️ Copyright & Public Domain Status
*   **The Original Text:** Maximillian Julius Otto Strutt's original German text was published in 1933. As of January 1, 2027, all foreign works published in 1933 that entered the US public domain have completed their 95-year term. The original work is globally recognized as being in the **Public Domain**.
*   **This Translation:** While the underlying mathematical ideas and original text are public domain, the creative phrasing of this specific English translation is copyright © 2026 David M. Day. 

---

### License
To ensure this work remains a free resource for the mathematical community, the translation text and LaTeX source code are dual-licensed under:
*   [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org) — For text content.
*   [MIT License](https://opensource.org) — For the underlying code/build structure.

### License
To ensure this work remains a free resource for the mathematical community, the translation text and LaTeX source code are dual-licensed under:
*   [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org) — For text content.
*   [MIT License](https://opensource.org) — For the underlying code/build structure.

You are free to share, copy, and modify this translation, provided you give appropriate credit.

---

## 🛠️ Compilation Instructions
To compile the document from the source files locally, ensure you have a standard LaTeX distribution installed (such as TeX Live or MacTeX) along with `biber` for bibliography processing.

Run the following commands in your terminal:
```bash
make
```

---

## 📝 Citation
If you use this translation in your academic work, cite both the original paper and this repository.

### BibLaTeX
```bibtex
@article{Strutt1933german,
  author       = {Strutt, M. J. O.},
  title        = {Eigenschwingungen einer Kegelschale},
  journal      = {Annals of Physics, Berlin},
  year         = {1933},
  volume       = {409},
  number       = {7},
  pages        = {729--735},
  note         = {modern numbering convention},
  langid       = {german},
  related      = {day2026translation},
  relatedtype  = {translatedas}
}

@misc{Day2026translation,
  author       = {Day, David M.},
  title        = {Natural Frequencies of a Thin Conical Shell},
  howpublished = {GitHub Repository},
  year         = {2026},
  url          = {https://github.com}
}
```

