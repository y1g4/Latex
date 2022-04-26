# Latex report and proposal templates
This is my undergraduate proposal and report template. I annotated the latex prologue and tried to keep it as basic as possible so that it could be understood and extended easily. The template contains dummy text with examples of how to create tables, figures, an index, and a glossary.

Please go to thesis.tex and change pdfauthur,pdftittle, and the pdf subjects

# Organization of the template
- Makefile governs the compiliation; target: dvi, ps and pdf
- thesis.tex holds everything together and includes
  - titlepage.tex
  - abstract.tex
  - acknowledge.tex
  - body.tex
- thesis-man.ist for custom formatting of Index (letter heading, dots)
- references.bib bibtex bibliography

# Features

The pdf file is fully hyperlinked
 - table of contents to chapters in the text
 - list of figures to figures in the text
 - list of tables to tables in the text
 - text to floats (figures and tables)
 - text to bibliograpy
 - bibliograpy to page in the text
 - index to page in the text
 - glossary to page in the text

# acrobat general information
 - thesis title
 - thesis subject
 - thesis author
 - thesis keyword
 
 small pdf file size
 
 # Anti-Features
I changed (but not necessarily improved) the standard latex layout by using bars over chapter titles etc.. This can be easily undone by deleting thesis.cls and changing in thesis.tex style thesis to style report

# Required software
- a flavor of unix for the makefile may be helpful
- latex and pdflatex
- non-standard packages: glossary.sty may need to be installed on teTeX, but comes with TexLive.
- ghostscript (thumbpdf)
- optional: zip and ps2ascii
