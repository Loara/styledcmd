# Styledcmd
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

## License

This file is part of Styledcmd.

Styledcmd is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

Styledcmd is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with Styledcmd. If not, see <https://www.gnu.org/licenses/>.
