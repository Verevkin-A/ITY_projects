NAME = proj2
LOGIN = xverev00

all:
	pdflatex $(NAME).tex
	pdflatex $(NAME).tex

zip:
	zip $(LOGIN)-fit.zip *.tex Makefile

clean:
	rm -f $(NAME).{aux,dvi,log,pdf,ps,out} $(LOGIN)-fit.zip
