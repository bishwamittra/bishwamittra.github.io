PAPERNAME=bghosh_teaching_statement
TEXFILES =  *.tex *.bib *.sty

all:
	pdflatex $(PAPERNAME)
	# bibtex $(PAPERNAME)
	# pdflatex $(PAPERNAME)
	# pdflatex $(PAPERNAME)
	rm -f *.ps $(PAPERNAME).dvi *.aux *.log *.blg *.bbl *~ *.ilg *.idx *.out *.in *.synctex.gz
clean:
	rm -f *.ps $(PAPERNAME).dvi *.aux *.log *.blg *.bbl *~ *.ilg *.idx *.out *.in *.synctex.gz

