# styledcmd
Handle multiple versions for user-defined macros in LaTeX

## Installation
Run one of the following commands in order to generate the `.sty` file

    pdflatex styledcmd.ins
    xelatex styledcmd.ins
    lualatex styledcmd.ins
    platex styledcmd.ins

il your distribution is up to date all these options should be equivalent, I personally recommend to use `lualatex` but is only a personal preference.

Anyway once you've generated the `.sty` file you've to add to your TeX distribution. In order to do it you have to know where your distribution stores all the user-installed packages, for example:

 * if you use `MiKTeX` you can follow these steps: https://tex.stackexchange.com/questions/2063/how-can-i-manually-install-a-package-on-miktex-windows
 * instead if you have `TeXLive` on Linux system go inside the `texmf/tex/latex` folder, create `styledcmd` subfolder and move in the preceding file.
