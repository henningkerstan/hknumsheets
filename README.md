# The hknumsheets Package
This LaTeX package provides a macro which expands to the total number of sheets required for double-sided printing of the document in which it is used.

## Usage
To use this package copy the file `numsheets.sty` into the same folder as your document (or, if you plan to use it more often, copy it into your local texmf directory) and load it by typing
```
\usepackage{hknumsheets}
```
anywhere in your document's preamble. Afterwards you can use the macro
```
\numsheets
```
anywhere in your document and it will expand to the number of sheets required for a double-sided printing of your document.

Note that this package loads the `lastpage` package.

### Further Information
For further information please read the package documentation in `hknumsheets.pdf` (you can either obtain this file from the GitHub releases page or simply compile the file `hknumsheets.tex` twice with pdflatex).

## Copyright and License
Copyright © 2017 Henning Kerstan.

This work may be distributed and/or modified under the conditions of the LaTeX Project Public License, either version 1.3 of this license or (at your option) any later version. The latest version of this license is in

[http://www.latex-project.org/lppl.txt](http://www.latex-project.org/lppl.txt)

and version 1.3 or later is part of all distributions of LaTeX version 2005/12/01 or later.

This work has the LPPL maintenance status ‘maintained’.

The Current Maintainer of this work is Henning Kerstan.

This work consists of the files 'hknumsheets.sty' and 'hknumsheets.tex'