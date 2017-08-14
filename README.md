# thesis
The code in this repository typesets my Ph.D. dissertation —
"The geochemistry of methane isotopologues", 
David T. Wang, MIT/WHOI Joint Program, June 2017 
(doi: [10.1575/1912/9052](http://dx.doi.org/10.1575/1912/9052))

**System** — pdfLaTeX + BibLaTeX/Biber from the TeX Live 2016 distribution on Windows 7

**Order of compilation**
1. `pdflatex makecover` (× 2)
3. `pdflatex main` 
4. `biber main`
5. `pdflatex main` (× 2+) <sup>note</sup>

<sup>note</sup> Typesetting `longtables` (e.g., Table 3.3) may require three or more passes through `pdflatex`.

Numbering in figure/table filenames may not match numbering in the produced thesis.  Some items have been re-numbered in revision.