TEX = /usr/texbin/pdflatex
LATEXMK = latexmk

mathics.pdf: mathics.tex documentation.tex
	$(LATEXMK) -pdf -pdflatex=$(TEX) mathics
	
latex: mathics.pdf

clear:
	rm -f mathics.asy mathics.aux mathics.idx mathics.log mathics.mtc mathics.mtc* mathics.out mathics.toc
	rm -f mathics.fdb_latexmk mathics.ilg mathics.ind mathics.maf mathics.pre
	rm -f mathics_*.*
	rm -f mathics-*.*
	rm –f mathics.pdf
