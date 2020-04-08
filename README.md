Thesis template
===============

## Requirements

- XeLateX or LuaLateX (the later is better at microtypography)
- biblatex
- Liberation serif font (tested version 2.00.1 ; download [here](https://github.com/liberationfonts/liberation-fonts/releases))
- Libertinus Math font (tested version v6.4 ; download [here](https://github.com/alif-type/libertinus/releases))

## Tex files

- UTF8
- Unix newline

## Compilation with XeLateX

`latexmk -xelatex -bibtex main.tex`

## Compilation with LuaLateX

`latexmk -lualatex -bibtex main.tex`

## Cleaning

`latexmk -c`
