NAME = proj3
LOGIN = xverev00

all:
	latex $(NAME).tex
	latex $(NAME).tex
	dvips $(NAME).dvi
	ps2pdf -sPAPERSIZE=a4 $(NAME).ps

zip:
	zip $(LOGIN)-fit.zip *.tex Makefile  algorithm2e.sty  etiopan.eps  oniisan.eps  oniisan2.eps

clean:
	rm -f $(NAME).{aux,dvi,log,pdf,ps,out} $(LOGIN)-fit.zip algorithm2e.sty  etiopan.eps  oniisan.eps  oniisan2.eps
