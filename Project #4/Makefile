NAME = proj4
LOGIN = xverev00

all:
	pdflatex $(NAME).tex
	bibtex $(NAME)
	pdflatex $(NAME).tex
	pdflatex $(NAME).tex

zip:
	zip $(LOGIN)-fit.zip *.tex $(LOGIN).bib czechiso.bst Makefile

clean:
	rm -f $(NAME).{aux,dvi,log,pdf,ps,out,bbl,bib,blg} czechiso.bst $(LOGIN)-fit.zip

