PAPERNAME=bghosh_cover_letter
TEXFILES =  *.tex *.bib *.sty

all:
	pdflatex $(PAPERNAME)
#	bibtex $(PAPERNAME)
	pdflatex $(PAPERNAME)
	pdflatex $(PAPERNAME)
	rm -f *.ps $(PAPERNAME).dvi *.aux *.log *.blg *.bbl *~ *.ilg *.idx *.out *.in *.synctex.gz
clean:
	rm -f *.ps $(PAPERNAME).dvi *.pdf *.aux *.log *.blg *.bbl *~ *.ilg *.idx *.out *.in *.synctex.gz

