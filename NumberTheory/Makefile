TEXFILENAME=main

default: one
one:
	pdflatex ${TEXFILENAME}
	make clean
clean:
	latexmk -c
	@rm -f *.dvi *.mw *.ps *.synctex
all:
	latexmk -pdf ${TEXFILENAME}