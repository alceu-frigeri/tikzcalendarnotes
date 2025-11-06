tikzcalendarnotes
==========

This package offers a "calendar arrangement" (atop of the TikZ calendar library) and  provides a set of commands aimed at highlighting/marking dates.

For more details , see the documentation ,
[tikzcalendarnotes.pdf](http://mirrors.ctan.org/graphics/pgf/contrib/tikzcalendarnotes/doc/tikzcalendarnotes.pdf)

--------------

## Requirements
* none besides a fairly recent LaTeX distribution as recent as 2022/06/01
(with the new in kernel *\ProcessKeyOptions* and *\NewDocumentCommand*).

## Installation
The stable version is available at [CTAN](https://ctan.org/pkg/tikzcalendarnotes).

## Usage
### Stable version
Just place
```latex
  \usepackage{tikz}
  \usetikzlibrary{calendar}
  ...
  \usepackage{tikzcalendarnotes}
```

in the preamble and compile away.

## Contacting Author

For bug reports and enhancement suggestions , the preferred way is to use
[the project's issue page](https://github.com/alceu-frigeri/tikzcalendarnotes/issues).
Please be ready to provide an example code showing the bug , if any.

Please do not use the issue page for generic help on how to use the package.

* git: https://github.com/alceu-frigeri/tikzcalendarnotes

-------------
Copyright 2025-present by Alceu Frigeri

 This work may be distributed and/or modified under the
 conditions of

 * The [LaTeX Project Public License](http://www.latex-project.org/lppl.txt) , version 1.3c (or later) , and/or
 * The [GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.html) , version 3 (or later)

This work has the LPPL maintenance status *maintained*.

The Current Maintainer of this work is Alceu Frigeri

-------------
## This work consist of the files

* tikzcalendarnotes.sty
    - the package itself

* README.md  (this file)
    - quick introduction

* tikzcalendarnotes.tex
* tikzcalendarnotes.bib
    - package documentation

* tikzcalendarnotes.pdf
    - documentation in PDF format
    
-------------

## Change log
* Version 1.2  (this)
    - small doc revision
    - code clean up (reducing the clutter) 

* Version 1.1 
    - switching over 'pkginfograb' package's info
    - removed expl3 scratch variables (\l_tmp...)
    - a bit better expansion control

* Version 1.0a
    - Documentantion: some emphasis towards ```pgfmanual``` standard key/styles. (issue [#1](https://github.com/alceu-frigeri/tikzcalendarnotes/issues/1)).


* Version 1.0 
    - Initial release by CTAN.
