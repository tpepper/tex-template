This repo's files are a simple template for writing a basic two-column
paper typeset in LaTeX.  Drop references in the mybib.bib file in standard
bibtex format (eg: copy/paste from Google Scholar) and modify the section
titles and body in the main .tex file.  Then render with commands like
(you can leave off the files' tex/dvi/etc extensions here):

``` bash
$  latex $filename
$  bibtex $filename
$  latex $filename
$  latex $filename
$  dvipdf $filename  #(alternatively MacTex has "dvipdft" executable here)
```
These commands are also sitting in a comment in the .tex file as a
reminder.

...and share the resulting $filename.pdf!
