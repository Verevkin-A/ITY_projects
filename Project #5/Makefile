NAME = proj5
LOGIN = xverev00

all:
	pdflatex $(NAME).tex
	pdflatex $(NAME).tex

zip:
	zip $(LOGIN)-fit.zip Binary_tree.png *.tex Makefile

clean:
	rm -f $(NAME).{aux,dvi,log,pdf,ps,out} $(LOGIN)-fit.zip
