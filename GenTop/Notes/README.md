# Files
The folder contains several files and folders:
 * README.md  - This file.
 * Bib.bib    - Bibloigraphy file, standard bibtex format.
 * main.tex   - The .tex file which generates the final document main.pdf
 * main.pdf   - The final pdf document
 * Content/   - Every section lives here
 * Lectures/  - Lecture notes live here
 * Pictures/  - Pictures live here
 * .Style.sty - Preamble for the latex file, contains definitions, "\usepackage" declarations, etc.
 * .compile   - compiles the .pdf file dangerously.

# Bibliograpy
To get natbib to work you'll need to run the following:
 > pdflatex main.tex
 > bibtex main
 > pdflatex main.tex
 > pdflatex main.tex
which fixes the bib-issues. Conversely, though not reccomended, you can run "sh .compile" which does the same but ignores errors in the latex file; use this at your own risk!


